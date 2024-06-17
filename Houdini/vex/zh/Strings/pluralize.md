---
title: pluralize
order: 23
---
`string  pluralize(string noun)`

The English language is full of nonstandard rules for pluralizing nouns. This function will properly create the plural ending for the input string. Only the end of the input string is used.
Examples

## examples

```vex
string boxes = pluralize("box");
string women = pluralize("woman");
string geometries = pluralize("geometry");

// Returns the string "Pluralize the last words"
string phrase = pluralize("Pluralize the last word");

```
