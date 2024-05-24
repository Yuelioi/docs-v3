---
display_name: depthmap
order: 2
---
`float  depthmap(string filename, vector uvw)`

`float  depthmap(string filename, float u, float v)`

The depthmap functions work on an image which was rendered as a z-depth
image from mantra. They return the floating point distance from the
camera to the pixel in question. There is no area sampling done when
sampling depth values. As well, if the u/v values are not in the range 0
to 1, a value of 1E6 will be returned (indicating a “far” value).
