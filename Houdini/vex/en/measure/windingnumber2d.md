---
display_name: windingnumber2d
order: 20
---
`float  windingnumber2d(<geometry>geometry, vector origin)`

`float  windingnumber2d(<geometry>geometry, vector origin, float accuracy)`

Computes the winding number of the curve geometry around the point origin.

`float  windingnumber2d(<geometry>geometry, string primgroup, vector origin)`

`float  windingnumber2d(<geometry>geometry, string primgroup, vector origin, float accuracy)`

Computes the winding number of primitive group primgroup around the point origin.

Show/hide arguments

`<geometry>`

When running in the context of a node (such as a wrangle SOP), this argument can be an integer representing the input number (starting at 0) to read the geometry from.

Alternatively, the argument can be a string specifying a geometry file (for example, a `.bgeo`) to read from. When running inside Houdini, this can be an `op:/path/to/sop` reference.

`primgroup`

Optionally compute winding number only for a subset of a curve specified by a primitive group.

`origin`

The position in space to compute winding number.

`accuracy`

The winding number is computed only approximately. The default value 2.0 is sufficient in most situations, setting accuracy to 12.0 should yield result accurate up to floating point precision.

Returns

The winding number of a curve at a point in XY plane.
