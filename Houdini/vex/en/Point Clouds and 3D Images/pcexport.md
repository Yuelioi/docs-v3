---
display_name: pcexport
order: 8
---
`int  pcexport(int handle, string channel_name, <type>value, ...)`

`int  pcexport(int handle, string channel_name, vector value, float radius, ...)`

Returns 1 if the export succeeded or 0 if the export failed.
The export will fail if channel_name is not read-write or if (in the
version of pcexport taking a radius) the point being exported is at a
distance less than the specified radius from a point that is already in the
point cloud.

This function writes to the channels of points opened with [pcopen](pcopen.html "Returns a handle to a point cloud file.") or
[pcgenerate](pcgenerate.html "Generates a point cloud."). The second version of this function takes a radius parameter and uses it to accept or reject the point being exported according to its distance to the points that are already in the point cloud. It must be separated from all other points by at least the specified radius. To write new point data into a point cloud file, use [pcwrite](pcwrite.html "Writes data to a point cloud file.").
Storage type

## storage-type

If you add the `"storage"` optional keyword, the next argument specifies a storage type for the data.
Storage types are the standard tile based format data types:

| `int8, uint8` | 8 bit signed/unsigned integers |
| --- | --- |
| `int16, uint16` | 16 bit signed/unsigned integers |
| `int32, uint32` | 32 bit signed/unsigned integers |
| `int64, uint64` | 64 bit signed/unsigned integers |
| `real16` | 16 bit floating point values |
| `real32` | 32 bit floating point values |
| `real64` | 64 bit floating point values |
| `int`, `uint`, `real` | Default precision integer/floating point values |
