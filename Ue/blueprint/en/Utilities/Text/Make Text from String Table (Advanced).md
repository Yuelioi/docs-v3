---
title: Make Text from String Table (Advanced)
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Text](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Text)

Attempts to create a text instance from a string table ID and key.
Note: This exists to allow programmatic look-up of a string table entry from dynamic content - you should favor setting your string table reference on a text property or pin wherever possible as it is significantly more robust (see "Make Literal Text").

Target is Kismet Text Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| name | Table Id |  |
| string | Key |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| text | Return Value | The found text, or a dummy text if the entry could not be found. |
