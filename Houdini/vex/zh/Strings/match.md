---
title: match
order: 20
---
`int  match(string pattern, string subject)`

This function returns 1 if the subject matches the pattern specified, or
0 if the subject doesn’t match. The standard Houdini pattern matching is
used. Multiple patterns may be separated by spaces or commas. The
special characters for matching are:

- `?` Match any character
- `*` Match any substring
- `[list]` Match any of the characters specified in the list.
- If a pattern is prefixed by a caret (^), then subjects which match
  this pattern will be excluded from the match.

Examples:

- `a*` - Match any string beginning with a.
- `a*,^aardvark` - Match any string beginning with a except for
  aardvark.
- `[abc]*z` - Match any string beginning with a, b or c and ending with
  z.
- `g*,^geo*` - Match any string beginning with g, but not any string
  beginning with geo.
