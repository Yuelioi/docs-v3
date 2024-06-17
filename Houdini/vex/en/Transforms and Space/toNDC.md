---
title: toNDC
order: 31
---
`vector  toNDC(vector point)`

`vector  toNDC(string camera_name, vector point)`

Transforms a position to the normal device coordinates for a camera.
The point should be in the local space of the object (i.e. not in the space of the camera).

toNDC() will return values above and below the 0-1 range outside the view of the camera or light. To the right of the camera are values of 1+ and to the left are values of 0-. The same goes for the range above and below the camera or light.

Transforms a position into normal device coordinates. This space is only
well-defined for the [shading contexts](../contexts/shading_contexts.html).
