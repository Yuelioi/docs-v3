---
display_name: Apply Color Wheel Delta
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Remote Control Color](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RemoteControlColor)

Add/subtract from the value of an FLinearColor property using a delta value based on color wheel coordinates.

Target is Remote Control Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Object | the object that contains the property to modify. |
| string | Property Name | the name of the property to modify. |
| struct | Delta Value | the amount to change the color by. |
| struct | Reference Color | if the color's current position on the wheel is ambiguous as calculated from RGB values (e.g. black), use this reference color's position instead. |
| boolean | Is Interactive | if true, this is treated as an interactive change. If false, it will be treated as the final value set change. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether the operation was successful. |
