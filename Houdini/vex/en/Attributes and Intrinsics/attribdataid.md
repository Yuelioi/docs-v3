---
title: attribdataid
order: 9
---
| Since | 17.0 |
| --- | --- |

`int [] attribdataid(<geometry>geometry, string attribclass, string attribute_name)`

Returns the data id corresponding to an attribute. Data ids can
be used for advanced forms of caching. If the data id of an attribute
is the same as you've seen before, you can assume the attribute
contains the same data it did before. This allows acceleration
structures to only be built when necessary.

The length and contents of the array are not defined, and no assumptions
should be made about the layout. The result will vary from run
to run of Houdini, so only exact equality should be used.

In addition to the normal attribute classes, an additional
attribute class of “meta” is supported. This has the additional
data ids of

topology

The overall wiring of vertices, points and primitives.
This will change if any points are rewired or vertices
added.

primitivelist

This data id changes if the contents of the primitive
change at all.

detail

This data id tracks the entire geometry as a whole. If
it is unchanged, no changes occurred in the geometry.

Show/hide arguments

`<geometry>`

When running in the context of a node (such as a wrangle SOP), this argument can be an integer representing the input number (starting at 0) to read the geometry from.

Alternatively, the argument can be a string specifying a geometry file (for example, a `.bgeo`) to read from. When running inside Houdini, this can be an `op:/path/to/sop` reference.

`attribclass`

One of `"detail"` (or `"global"`), `"point"`, `"prim"`, or `"vertex"`.

You can also use `"primgroup"`, `"pointgroup"` or `"vertexgroup"` to [read from groups](../groups.html "You can read the contents of primitive/point/vertex groups in VEX as if they were attributes.").

`attribute_name`

The name of the attribute (or intrinsic) to read.

Returns

An integer array indicating the data id of the attribute.
