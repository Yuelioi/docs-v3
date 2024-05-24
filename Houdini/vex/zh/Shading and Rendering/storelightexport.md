---
display_name: storelightexport
order: 75
---
| Context(s) | [displace](../contexts/displace.html)  [fog](../contexts/fog.html)  [surface](../contexts/surface.html) |
| --- | --- |

`void  storelightexport(string lightname, string exportname, <type>value)`

`void  storelightexport(string lightname, string exportname, <type>value[])`

Stores a per-light export to a shader export variable. This method should
normally be called for each light to ensure that all light exports for the
given variable are created, for example by placing the call in an
illuminance() loop or a loop over the light array.

This method replaced the `storelightexports()` method used in Houdini 12.5 and earlier.
Examples

## examples

```vex
surface test(export vector perlight = {0,0,0})
{
    int             lights[] = getlights();
    for (int i = 0; i < len(lights); i++)
    {
        vector val = set(lights[i], 0, 0);
        storelightexport(getlightname(lights[i]), "perlight", val);
    }
}

```
