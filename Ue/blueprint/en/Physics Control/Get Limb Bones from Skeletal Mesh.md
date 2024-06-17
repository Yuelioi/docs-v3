---
title: Get Limb Bones from Skeletal Mesh
order: 46
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Calculates which bones belong to which limb in a skeletal mesh

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | Skeletal Mesh Component | The skeletal mesh which will be analyzed |
| struct | Limb Setup Data | This needs to be filled in with the list of limbs to "discover". Note that the limbs should be listed starting at the "leaf" (i.e. outer) parts of the skeleton first, typically finishing with the spine. In addition, the spine limb is typically specified using the first spine bone, but flagging it to include its parent (normally the pelvis). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| name | Return Value | A map of limb names to bones |
