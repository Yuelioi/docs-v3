---
title: select
order: 16
---
`<type> select(int conditional, <type>a, <type>b)`

`<type>[] select(int conditional, <type>a[], <type>b[])`

Returns `a` if the conditional is true, and returns `b` if it is false.

The difference between select and an `if` statement is that select will
evaluate both a and b, regardless of the value of the conditional. Judicious
use of `select` can avoid comparisons, allowing larger sections of code to be
converted to native code.
