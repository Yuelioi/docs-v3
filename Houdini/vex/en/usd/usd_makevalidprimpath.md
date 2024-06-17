---
title: usd_makevalidprimpath
order: 91
---
| Since | 19.0 |
| --- | --- |

`string  usd_makevalidprimpath(string path, int allow_relative)`

This function ensures that a string meets the requirements of a legal USD
primitive path that can be passed to other USD functions.

Show/hide arguments

`path`

String that should be turned into a valid primitive path.

`allow_relative`

If this value is non-zero, the string is allowed to represent a relative
primitive path. A relative path is one that starts with `./` or `../`. If
this argument is zero, only absolute paths (which start with `/`) are
allowed. Relative prefixes are simply removed from the path and the
returned path will always start with a `/`.

Returns

A possibly modified version of the original string which conforms to the
requirements for USD primitive paths. Invalid characters such as spaces
and most punctuation will be converted to underscores. Note that this means
the translation is not reversible. If the original string is already a
legal primitive path, the string is returned unchanged.
