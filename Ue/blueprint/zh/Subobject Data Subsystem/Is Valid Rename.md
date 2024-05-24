---
display_name: Is Valid Rename
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Subobject Data Subsystem](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SubobjectDataSubsystem)

Returns true if the given new text is a valid option to rename the
subobject with the given handle. Populates the OutErrorMessage if
it is not valid.

Target is Subobject Data Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Handle | Handle to the subobject that is being checked |
| text | In New Text | The new name that is desired |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| text | Out Error Message | The reasoning for an invalid name |
| boolean | Return Value | True if the rename is valid |
