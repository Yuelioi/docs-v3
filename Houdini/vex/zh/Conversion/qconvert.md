---
display_name: qconvert
order: 7
---
`matrix3  qconvert(vector4 quaternion)`

Converts a quaternion represented by a vector4 to a matrix3 representation.

`matrix  qconvert(vector4 quaternion, vector offset)`

Converts a quaternion represented by a vector4 to a matrix representation.
Applies the offset as a post-translation, so the resulting matrix will
first rotate a point by the quaternion and then add the offset.

`vector  qconvert(vector4 quaternion)`

Converts a quaternion represented by a vector4 into a angle/axis vector.
