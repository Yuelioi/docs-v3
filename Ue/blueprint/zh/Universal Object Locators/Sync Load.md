---
display_name: Sync Load
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Universal Object Locators](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UniversalObjectLocators)

Attempt to resolve the object locator by finding or loading the object.

Target is Universal Object Locator Scripting Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Locator |  |
| object | Context | (Optional) Context object to use for resolving the object. This should usually be the object that owns or created the locator. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | The resolve object pointer, or null if it was not found. |
