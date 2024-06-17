---
title: ord
order: 22
---
`int  ord(string value)`

Returns the code point of the first UTF8 character in the given string.

If the prefix of the string isn’t a valid UTF8 encoding, or is empty, -1 is returned.

Overlong UTF8 encodings will return -1.
