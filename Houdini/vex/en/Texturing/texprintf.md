---
title: texprintf
order: 12
---
`string  texprintf(float u, float v, string format, ...)`

Formats a string like [sprintf](sprintf.html "Formats a string like printf but returns the result as a string
instead of printing it."), but scans for special conversion
characters to perform either UDIM or UVTILE style filename expansion.

This can be significantly more efficient than calling sprintf() directly.

The special conversion sequences are:

`<UDIM>`

The UDIM coordinate, as computed by `1000 + int(u)+1 + int(v)*10`

`%(U)d`

The UVTILE style u-coordinate (`int(u)+1`)

`%(V)d`

The UVTILE style v-coordinate (`int(v)+1`)

`%(UVTILE)d`

Expands to both u and v coordinates in the form `u%d_v%d`.

The `d` conversion specifier for texture identification can be modified with
field modifiers. For example `%(U)02d` or `%(V)04d`.
Examples

## examples

```vex
!vex
// Returns "map_1044.rat
texprintf(3.1, 4.15, "map_<UDIM>.rat");

// Returns "map_04_05.rat"
texprintf(3.1, 4.15, "map_%(U)02d_%(V)02d.rat");

// Returns "map_u4_v12.rat"
texprintf(3.14, 11.5, "map_u%(U)d_v%(V)d.rat");

// Returns "/path/basename_04_05.rat"
texprintf(3.1, 4.1, "%s/%s_%(U)02d_%(V)02d.rat", "/path", "basename");

// Returns "/path/basename_u04_v05.rat"
texprintf(3.1, 4.1, "%s/%s_%(UVTILE)02d.rat", "/path", "basename")
```

```vex
string map = texprintf(u, v, "%s/%s_<UDIM>.rat", texture_path, texture_base);
Cf = texture(map, u, v);

```
