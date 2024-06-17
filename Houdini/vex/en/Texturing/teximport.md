---
title: teximport
order: 11
---
| On this page | * [Queryable attributes](#queryable-attributes) * [Examples](#examples) |
| --- | --- |

`int  teximport(string map, string attribute, <type>&value)`

Reads a single value. Returns `1` on success or `0` on failure.

`int  teximport(string map, string token, int|string&values[])`

Returns the number of strings in the array.

Note that if the values cannot be imported, `values` will not be written to and may remain uninitialized.

This function queries metadata stored in an image file, and works with most texture formats.

You can choose what properties are stored using the `vm_saveoptions`
Houdini property on a camera or light
(`image:saveoptions` in [IFD](../../render/ifd.html)).
However, the defaults probably contain all the information you'd want.
See [rendering properties](../../props/index.html "Properties let you set up flexible and powerful hierarchies of rendering, shading, lighting, and camera parameters.").
Queryable attributes

## queryable-attributes

There are several generic attributes you can always query:

Show/hide arguments

`int texture:xres`

X resolution of the texture map.

`int texture:yres`

Y resolution of the texture map.

`int texture:channels`

Number of channels in the texture map.

`vector texture:resolution`

Resolution of the texture as the vector `(xres, yres, channels)`.

`matrix texture:worldtoview`

The transform matrix that will take world space points into the camera
space used to generate the image.

`matrix texture:projection`

The transform matrix representing the projection matrix of the camera
used to generate the image.

`matrix texture:worldtondc`

The transform matrix that will transform world spaced points into the NDC (Normalized Device Coordinates) space of the camera used to make the image. The points are generated in homogeneous coordinates. That is, to get the values in the range 0 to 1:

```vex
matrix ndc;
if (teximport(map, "texture:worldtoNDC", ndc))
{
    vector P_ndc = pos * ndc;
    // If the camera is a perspective camera,
    // dehomogenize the point
    if (getcomp(ndc, 2, 3) != 0)
    {
        P_ndc.x = P_ndc.x / P_ndc.z;
        P_ndc.y = P_ndc.y / P_ndc.z;
    }
    // Finally, scale and offset XY
    // from [-1,1] to [0,1]
    P_ndc *= {.5, .5, 1};
    P_ndc += {.5, .5, 0};
}

```

`string texture:tokens`

A space separated list of all attribute names you can query.

The `string &values[]` version can query the following

`texture:channelnames`

List of all the raster plane channel names.

`texture:channelsize`

This returns an array of the number of floats in each image channel.

`texture:channelstorage`

This returns an array with a string for the underlying storage type for
each channel (i.e. `uint8` or `real16`).

`texture:channelcolorspace`

An array of the color space associated with each channel.

`texture:tokens`

List of all the built-in tokens understood by `teximport()`.

Show/hide arguments

`string texture:device`

The device that’s used to evaluate the texture. Possible values are:

- `native` - Evaluated using the built-in Houdini texture engine
- `oiio` - Evaluated using OpenImageIO
- `ptex` - Evaluated using Ptex

`string: texture:colorspace`

This is the color space the texture library will use by default. That is, when the `srccolorspace` keyword argument isn’t provided.

`string: texture:swrap`

Some texture formats store metadata that provides the default wrap mode for texture coordinates. This key will lookup the value in the metadata for wrapping in s (or an empty string).

`string: texture:twrap`

Some texture formats store metadata that provides the default wrap mode for texture coordinates. This key will lookup the value in the metadata for wrapping in t (or an empty string).

Examples

## examples

```vex
cvex
 test(string map="Mandril.rat")
{
    for (string token : {
                    "texture:xres",
                    "texture:yres",
                    "texture:channels",
                    "texture:resolution",
                    "texture:tokens",
                    "image:pixelaspect",
                    "space:world"
                })
    {
        float fval;
        vector vval;
        matrix mval;

        printf("----------------- %s ---------------------\n", token);
        if (teximport(map, token, fval))
            printf("'%s' = %g\n", token, fval);
        else if (teximport(map, token, vval))
            printf("'%s' = %g\n", token, vval);
        else if (teximport(map, token, mval))
            printf("'%s' = %g\n", token, mval);
    }
}

```
