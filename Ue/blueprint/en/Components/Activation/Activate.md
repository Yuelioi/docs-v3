---
display_name: Activate
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Activation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/Activation)

Activates the SceneComponent, should be overridden by native child classes.

Target is Actor Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Reset | Whether the activation should happen even if ShouldActivate returns false. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
