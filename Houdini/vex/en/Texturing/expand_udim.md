---
title: expand_udim
order: 4
---
`string  expand_udim(float u, float v, string path, ...)`

Scans the input path for special conversion characters to perform either UDIM
or UVTILE style filename expansion.

This is similar to [texprintf](texprintf.html "Similar to sprintf, but does expansion of UDIM or UVTILE texture filename expansion."), with two significant differences:

- There are no variadic print arguments. Only UDIM/UVTILE expansion is performed.
- If UDIM/UVTILE expansion was performed, the function checks to see if the texture exists and is accessible.

Show/hide arguments

`u`, `v`

The texture coordinates to translate into a UDIM tile specification.

`path`

A file path. Special character sequences in the path will be expanded into UDIM specifiers based on the given UV coordinates. The special conversion sequences are:

| `%(UDIM)d` or `<UDIM>` | The UDIM coordinate, as computed by `1000 + int(u)+1 + int(v)*10` |
| --- | --- |
| `%(U)d` | The UVTILE style u-coordinate (`int(u)+1`) |
| `%(V)d` | The UVTILE style v-coordinate (`int(v)+1`) |
| `%(UVTILE)d` or `<UVTILE>` | Expands both u and v coordinates in the form `u%d_v%d`. |

The `d` conversion specifier for texture identification can be modified with
field modifiers. For example `%(U)02d` or `%(V)04d`.

"checkfile",
`int`
`=1`

Normally, the function checks whether the expanded path exists and is readable. If you pass the `"checkfile", 0` pair, the function will not perform this check.

Returns

The path with any UDIM control sequences replaced.

If the expanded file path does not exist or is not readable, the function will return an empty string, unless you turn off the `checkfile` variadic argument.

Examples

## examples

- `expand_udim(3.1, 4.15, "map_<UDIM>.rat")` - Returns “map_1044.rat”
- `expand_udim(3.1, 4.15, "map_%(U)02d_%(V)02d.rat")` - Returns “map_04_05.rat”
- `expand_udim(3.14, 11.5, "map_u%(U)d_v%(V)d.rat")` - Returns “map_u4_v12.rat”
- `expand_udim(3.14, 11.5, "missing_file<UDIM>.rat")` - Returns “” for missing files.
- `expand_udim(3.14, 11.5, "missing_file<UDIM>.rat", "checkfile", 0)` - Returns “missing_file1044.rat” since “checkfile” is disabled.
- `expand_udim(3.14, 11.5, "/path/file.rat")` - Returns “/path/file.rat” whether the file exists or not since there are no UDIM/UVTILE expansions.

```vex
// sprintf() will leave the %(UDIM)d format sequence unmodified.
string map = sprintf("%s/%s_%(UDIM)d.rat", texture_path, texture_base);
// Expand the <UDIM>, returning an empty string if the map doesn't exist.
map = expand_udim(u, v, map);
if (map != "")
Cf = texture(map, u, v);

```
