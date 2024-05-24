---
display_name: Use Blackboard
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI)

Makes AI use the specified Blackboard asset & creates a Blackboard Component if one does not already exist.

Target is AIController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Blackboard Asset | The Blackboard asset to use. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Blackboard Component | The Blackboard component that was used or created to work with the passed-in Blackboard Asset. |
| boolean | Return Value | true if we successfully linked the blackboard asset to the blackboard component. |
