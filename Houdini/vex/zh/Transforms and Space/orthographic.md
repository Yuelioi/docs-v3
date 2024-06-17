---
title: orthographic
order: 10
---
| Since | 17.5 |
| --- | --- |

`matrix  orthographic(float zoom, float orthowidth, float image_aspect, float pixel_aspect, float clip_near, float clip_far)`

`matrix  orthographic(float zoom, float orthowidth, float image_aspect, float pixel_aspect, float clip_near, float clip_far, vector4 window)`

Create an orthographic projection matrix with the given parameters. This can be used to project points onto the so-called NDC coordinates of a camera.

To make a single transform from world space to NDC space given a camera matrix and a projection matrix, you would use, `worldToNDC = worldToCamera * projection;`

Show/hide arguments

`zoom`

The zoom for the lens. Sometimes the zoom is expressed in terms of focal and aperture. In this case, `zoom = focal/aperture`.

`orthowidth`

An additional “zoom” factor.

arg:image_aspect

The aspect ratio of the image. Sometimes the image_aspect is expressed in terms of `xres` and `yres`. In this case, `image_aspect = xres / yres`.

arg::clip_near

The near clipping plane.

arg::clip_far

The far clipping plane.

arg::window

The offset for the projection window encoded in a vector4.
window.x and window.y are the window min xy coordinates and
window.z, window.w are the window max xy coordinates.
This argument is optional and defaults to {0,0,1,1} when not given.
