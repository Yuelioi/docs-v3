---
title: resize
order: 13
---
`void  resize(<type>&array[], int size)`

Changes the size of the given array. If `size` is greater than the current length of the array, the extra items at the end of the array will be initialized to default values of the given type (for example, `0`, empty string, `{0,0,0}`, etc.).

`void  resize(<type>&array[], int size, <type>val)`

Changes the size of the given array. If `size` is greater than the current length of the array, the extra items at the end of the array will be initialized to `val`.
