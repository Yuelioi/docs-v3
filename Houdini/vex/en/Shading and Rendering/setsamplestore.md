---
title: setsamplestore
order: 69
---
| Context(s) | [shading](../contexts/shading.html) |
| --- | --- |

`int  setsamplestore(string channel, vector P, int value)`

`int  setsamplestore(string channel, vector P, float value)`

`int  setsamplestore(string channel, vector P, vector value)`

`int  setsamplestore(string channel, vector P, vector4 value)`

Stores a value in a named channel at a specified point.
Returns a non-zero value on success, or returns 0 if the data could not be set.

The sample store can be thought of as an in-memory point cloud, storing
shading data at points. This allows data to be accessed across shader
boundaries, unlike the internal export/import system. For example,
a lens shader could store data to be passed to the surface shader,
an operation that is not supported using export variables due to the
layout of the shading pipeline.

Please note that the stored samples can only be accessed within the same render
tile.
Example

## example

```vex
cvex displacedlens(
    // Inputs
    float x = 0;
    float y = 0;
    float Time = 0;
    float dofx = 0;
    float dofy = 0;
    float aspect = 1;

    float displaceScale = 1.0;
    float displaceGain = 0.1;

    // Outputs
    export vector P = 0;
    export vector I = 0;
)
{
    P = {x, y, 0};
    I = {1, 0, 0};

    vector displace = noise(P * displaceScale) * displaceGain;
    I += displace;

    // Store the displacement at the eye point, 'P'
    int status = setsamplestore("displacedlens_d", P, displace);
}

surface mysurface()
{
    // Get the displacement at the eye point, 'Eye'
    vector displace = 0;
    int status = getsamplestore("displacedlens_d", Eye, displace);

    //...
}

```
