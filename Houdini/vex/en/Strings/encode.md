---
title: encode
order: 8
---
| Since | 17.5 |
| --- | --- |

`string  encode(string str)`

Houdini VEX variable names are only allowed to contain letters, numbers, and
underscores, and must not begin with a number. This function takes any string,
and encodes it into a string that obeys these restrictions. The original
string can be recovered using the `decode` function. A string that already
obeys the rules is returned unmodified.

One exception to this rule is that a string starting with `xn__` will be
encoded even if it is already a valid variable name. This is because `xn__`
is the prefix used to identify an encoded string. In this case, an additional
`xn__` prefix will be added. This means a string can be encoded any number of
times, then decoded the same number of times to always return to the original
string, regardless of its contents.
