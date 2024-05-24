---
display_name: setpointattrib
order: 67
---
If you don’t know the attribute class ahead of time, use [setattrib](setattrib.html "Writes an attribute value to geometry.").

`int  setpointattrib(int geohandle, string name, int point_num, <type>value, string mode="set")`

`int  setpointattrib(int geohandle, string name, int point_num, <type>value[], string mode="set")`

Returns the value of `geohandle` on success or `-1` on failure.

Note
If the attribute does not exist, this function **creates the attribute** with a default value of zero, empty string, or an empty array.
If you want to control the default value of a numeric attribute, use [addattrib](addattrib.html "Adds an attribute to a geometry.") before setting the attribute.

If the attribute does not already exist, its type info is automatically set for attributes with [standard names](../snippets.html#known) such as `Cd` and `orient`.
If you want to control the type info of a numeric attribute, use [setattribtypeinfo](setattribtypeinfo.html "Sets the meaning of an attribute in geometry.") before setting the attribute.

Show/hide arguments

`geohandle`

A handle to the geometry to write to. Currently the only valid value is `0` or [geoself](geoself.html "Returns a handle to the current geometry."), which means the current geometry in a node. (This argument may be used in the future to allow writing to other geometries.)

`name`

The attribute to set on the given point.

`point_num`

The number of the point to set the attribute on.

`value`

The value to set the attribute to.

Note that within a VEX program only one type may be written to a single attribute. Ie, you cannot mix writes of float an integer. This can be surprising as a literal like `1` will be an integer write so be ignored if floats were previously written.

`mode`

(Optional) if given, this controls how the function modifies any existing value in the attribute.

| `"set"` | Overwrite the attribute with the given value. |
| --- | --- |
| `"add"` | Add to the attribute the value. |
| `"min"`, `"minimum"` | Set the attribute to the minimum of itself and the value. |
| `"max"`, `"maximum"` | Set the attribute to the maximum of itself and the value. |
| `"mult"`, `"multiply"` | Multiply the attribute by the value. For matrices, this will do matrix multiplication. For vectors, component-wise. |
| `"toggle"` | Toggles the attribute, independent of the source value. Useful for toggling group membership. |
| `"append"` | Valid for string, dict, and array attributes. For strings and  arrays, appends the source value to the end of the original  value. For dictionaries, updates the original dictionary with  the source dictionary, replacing any matching keys. |
