---
display_name: hedge_presrcpoint
order: 11
---
`int  hedge_presrcpoint(<geometry>geometry, int hedge)`

Show/hide arguments

`<geometry>`

When running in the context of a node (such as a wrangle SOP), this argument can be an integer representing the input number (starting at 0) to read the geometry from.

Alternatively, the argument can be a string specifying a geometry file (for example, a `.bgeo`) to read from. When running inside Houdini, this can be an `op:/path/to/sop` reference.

`hedge`

Input half-edge.

Returns

The point of the point into which the vertex that comes before the source vertex of the `hedge` in the primitive that contains `hedge` is wired.
Returns `-1` if the half-edge is not valid.

Examples

## examples

```vex
int presrcpt;

// Get the pre-source point of half-edge number 3.
presrcpt = hedge_presrcpoint("defgeo.bgeo", 3);

```
