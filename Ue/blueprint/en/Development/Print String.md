---
title: Print String
order: 50
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Development](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Development)

Prints a string to the log, and optionally, to the screen
If Print To Log is true, it will be visible in the Output Log window. Otherwise it will be logged only as 'Verbose', so it generally won't show up.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | In String | The string to log out |
| boolean | Print to Screen | Whether or not to print the output to the screen |
| boolean | Print to Log | Whether or not to print the output to the log |
| linearcolor | Text Color | The color of the text to display |
| real | Duration | The display duration (if Print to Screen is True). Using negative number will result in loading the duration time from the config. |
| name | Key | If a non-empty key is provided, the message will replace any existing on-screen messages with the same key. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
