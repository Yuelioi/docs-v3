---
display_name: Get Property from Root
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Concert](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Concert) > [Replication](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Concert/Replication)

Gets the property at Index starting from the root most property.
Example: The root Index 0 for \["RelativeLocation", "X"\] would return "RelativeLocation".

Target is Concert Replication Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Path | The property path to get the sub-property from. |
| integer | Index | The index in the path counting from the left, root property. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| name | Return Value | The property name at Index or None if Index is invalid. |
