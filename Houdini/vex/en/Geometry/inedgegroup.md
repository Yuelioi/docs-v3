---
display_name: inedgegroup
order: 7
---
`int  inedgegroup(string filename, string groupname, int pointnum0, int pointnum1)`

`int  inedgegroup(int input, string groupname, int pointnum0, int pointnum1)`

Returns 1 if the edge specified by the point pair is in the group specified by the string. This function returns 0 if the group does not exist or if the edge is not contained in the group.

This can use ad-hoc groups, like `p29-30`. It matches the SOP group naming
convention, in particular that an empty string means all edges.
