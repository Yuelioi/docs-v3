---
title: Create Controls and Body Modifiers from Control Profile Asset
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

This uses the control profile asset (that should have already been set) to create
controls and body modifiers
It is also possible to specify a mesh component to use for the "world" object - so that the world controls can
be made to work in the space of another object (or a bone if that is a skeletal mesh component)

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Skeletal Mesh Component |  |
| object | World Component |  |
| name | World Bone Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
