---
title: opstart
order: 9
---
| Context(s) | [shading](../contexts/shading.html) |
| --- | --- |

`int  opstart(string message)`

Inform mantra about the start of a long operation (operation start). The string argument is passed to mantra and may be displayed in the IPR viewer.

The function will return a non-negative integer when successfully started.

The integer returned should be passed to `opend()` at the completion of the long operation.

```vex
int started = opstart("Performing long operation");
perform_long_operation();
if (started >= 0)
opend(started);

```
