---
display_name: Create Body Modifiers from Skeletal Mesh Below
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Creates new body modifiers for skeletal mesh components

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Skeletal Mesh Component | The skeletal mesh which will have body modifiers |
| name | Bone Name | The bone name below which modifiers should be created |
| boolean | Include Self | Whether or not to include BoneName when creating modifiers |
| name | Set | Which set to include the body modifier in (optional). Note that it automatically gets added to the set "All" |
| struct | Body Modifier Data | The initial properties of the modifier |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| name | Return Value |  |
