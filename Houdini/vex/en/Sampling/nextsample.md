---
display_name: nextsample
order: 5
---
| Context(s) | [displace](../contexts/displace.html)  [fog](../contexts/fog.html)  [light](../contexts/light.html)  [shadow](../contexts/shadow.html)  [surface](../contexts/surface.html) |
| --- | --- |

`void  nextsample(int &sid, float &sx, float &sy, ...)`

`void  nextsample(int &sid, vector &svec, ...)`

[newsampler](newsampler.html "Initializes a sampling sequence for the nextsample function.") and this function expose the high-quality deterministic sampling patterns used by mantra for pixel anti-aliasing. When rendering in raytracing mode, it’s possible to generate deterministic 2D samples with `nextsample` routine by initializing the sampling sequence with the `SID` global variable.

This method can generate either 2D or 3D sampling patterns. To generate 2D samples, use the signature with 2 float write-only arguments. To generate 3D samples, use the signature with a vector write-only argument.

You can add an extra argument, `"mode"`, followed by one of the following:

Show/hide arguments

`“qstrat”`

Advances to the next sample in the pattern. You should use this mode when using [newsampler](newsampler.html "Initializes a sampling sequence for the nextsample function.").

`“nextpixel”`

Advances to a new pixel sampling pattern. You should use this mode when using SID with raytracing to generate good-quality sampling patterns within a pixel. This mode takes into account other samples within the current pixel and will appropriately stratify itself. If rendering with micropolygon rendering, “nextpixel” will behave the same as “qstrat”.

`“decorrelate”`

Advances to a new decorrelated sample. You should use this mode to deterministically generate a new sampling sequence that is unrelated to an existing sequence. Similarly to “nextpixel”, this mode preserves high-quality pixel sampling when used with SID and raytracing.

```vex
int nsamples = 10;
int sid = israytrace ? SID : newsampler();

for (i = 0; i < nsamples; i++)
{
if (israytrace)
nextsample(sid, sx, sy, "mode", "nextpixel");
else
nextsample(sid, sx, sy, "mode", "qstrat");
// Sample something using sx/sy...
}

```
