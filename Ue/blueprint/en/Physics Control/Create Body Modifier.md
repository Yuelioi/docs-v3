---
display_name: Create Body Modifier
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Creates a new body modifier for mesh components

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Mesh Component | The Mesh Component used as a target for the modifier |
| name | Bone Name | The bone name, if a skeletal mesh is used |
| name | Set | Which set to include the body modifier in (optional). Note that it automatically gets added to the set "All" |
| struct | Body Modifier Data | The initial properties of the modifier |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| name | Return Value |  |
