---
display_name: Update Controls
order: 123
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Allows manual ticking so that your code can run in between updating the target caches and updating
the controls and body modifiers. This allows you to read the targets coming from animation and use
those values to create your own controls etc.

To use this function, you should disable ticking of the Physics Control Component, and ensure that the
relevant Skeletal Mesh Component (if being used) has ticked, using a tick prerequisite. Then explicitly
call (in order) UpdateTargetCaches and UpdateControls as you process your tick.

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Delta Time |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
