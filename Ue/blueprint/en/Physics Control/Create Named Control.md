---
display_name: Create Named Control
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Creates a new control for mesh components

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name |  |
| object | Parent Mesh Component |  |
| name | Parent Bone Name |  |
| object | Child Mesh Component |  |
| name | Child Bone Name |  |
| struct | Control Data | Describes the initial strength etc of the new control |
| struct | Control Target | Describes the initial target for the new control |
| name | Set | Which set to include the control in (optional). Note that it automatically gets added to the set "All" |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if a new control was created, false if a control of the specified name already exists |
