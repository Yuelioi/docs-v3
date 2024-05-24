---
display_name: Find Smart Objects in List
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Search list of specific actors (often from a physics query) for slot candidates respecting request criteria and selection conditions.

Target is Smart Object Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Filter | Parameters defining the search area and criteria |
| object | Actor List | Ordered list of actors to search |
| object | User Actor |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Results | List of smart object slot candidates found in range |
| boolean | Success | True if at least one candidate was found. |
