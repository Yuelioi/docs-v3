---
display_name: usd_getbbox
order: 42
---
| Since | 18.0 |
| --- | --- |

`int  usd_getbbox(<stage>stage, string primpath, string purpose, vector &min, vector &max)`

This function returns primitive’s axis-aligned bounding box. The point corresponding to the minimum corner of the bounding box will be returned in min, while the maximum will be in max. Always returns 1.

Show/hide arguments

`<stage>`

When running in the context of a node (such as a wrangle LOP), this argument can be an integer representing the input number (starting at 0) to read the stage from. The integer is equivalent to the string form referencing a particular input, e.g., “opinput:0”.

You can also use this argument to refer to a USD file (e.g., “/path/to/file.usd”), or to another LOP node’s cooked stage using the `op:` as the path prefix (e.g., “op:/stage/lop_node”).

`primpath`

The path to the primitive.

`purpose`

The primitive’s purpose for which to return the bounding box (e.g., “render”).

Returns

Always 1.

Examples

## examples

```vex
// Get the sphere's bounding box.
vector min, max;
usd_getbbox(0, "/src/sphere", "render", min, max);

```
