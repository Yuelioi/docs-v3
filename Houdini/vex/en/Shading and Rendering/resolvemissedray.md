---
display_name: resolvemissedray
order: 66
---
| Context(s) | [shading](../contexts/shading.html) |
| --- | --- |

`vector  resolvemissedray(vector dir, float time, int mask, ...)`

Returns the color of the background environment for rays that exit the
scene. When no environment or background color is specified, any
environment lights in the scene using the mode “Ray Tracing Background”
will be used to look up the environment color. mask indicates the type
of ray that is being resolved as an integer mask.

To use the default background (environment light) for a reflection ray:

```vex
resolvemissedray(I, 0.0, PBR_REFLECT_MASK);
```

To define your own background:

```vex
resolvemissedray(I, 0.0, PBR_ALL_MASK, "environment", "Mandril.rat", "envtint", {1,2,1});
resolvemissedray(I, 0.0, PBR_ALL_MASK, "background", {1,1,1});
```
