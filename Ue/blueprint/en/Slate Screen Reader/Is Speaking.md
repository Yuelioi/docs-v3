---
title: Is Speaking
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Slate Screen Reader](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SlateScreenReader)

Returns true if the screen reader is speaking text to a particular user.
Returns false if no no announcements are being spoken to the user or if the user Id is not registered.

Target is Slate Screen Reader Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Screen Reader User Id | The user Id of the screen reader user to check if any announcements are being spoken to. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value |  |
