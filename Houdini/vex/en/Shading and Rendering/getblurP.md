---
display_name: getblurP
order: 10
---
| Context(s) | [displace](../contexts/displace.html)  [fog](../contexts/fog.html)  [light](../contexts/light.html)  [shadow](../contexts/shadow.html)  [surface](../contexts/surface.html) |
| --- | --- |

`vector  getblurP(float delta)`

Returns the position (`P`) of the current shading point at fractional time delta within the motion blur exposure. When motion blur is disabled, `getblurP()` will always return the shading position `P`. When motion blur is enabled, `getblurP(0)` and `getblurP(1)` will return the positions at the extent of the shading position’s motion path, with fractional values between 0 and 1 generating other intermediate shading positions. For example, `getblurP(0.5)` returns the point’s blurred position half-way through the current exposure.

When shading micropolygons, `P` will always store the initial position of the point (at time = 0). For raytracing, `P` will store the final position after motion transformation for the sample being shaded - at the time given by the `Time` global variable in the VEX shading context. If you want to determine the shading position at other times it is necessary to use `getblurP`.

When using point clouds that were generated at time = 0, you should use `getblurP(0)` to find the position at the start of the frame’s exposure and then use this position to look up in the point cloud.

For example:

```vex
vector p0 = getblurP(0);
int handle = pcopen("pcloud.pc", p0, ...);
```
