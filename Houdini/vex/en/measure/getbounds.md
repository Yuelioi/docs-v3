---
display_name: getbounds
order: 8
---
`int  getbounds(string filename, vector &min, vector &max)`

`int  getbounds(string filename, string group, vector &min, vector &max)`

Returns the bounding box of the geometry specified by the filename. The
point corresponding to the minimum corner of the bounding box will be
returned in min, while the maximum will be in max.
Always returns 1.

If a group is specified, only primitives in that group will be used.
The group field’s behavior matches that in SOPs. An empty string
will include all primitives. Ad-hoc patterns like `0-10` and
`@Cd.x>0` are also valid.

The `getbbox()` function should likely be used instead.
