---
title: Get Anim Instance
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skeletal Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkeletalMesh)

Returns the animation instance that is driving the class (if available). This is typically an instance of
the class set as AnimBlueprintGeneratedClass (generated by an animation blueprint)
Since this instance is transient, it is not safe to be used during construction script

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Returns the animation instance that is driving the class (if available). This is typically an instance ofthe class set as AnimBlueprintGeneratedClass (generated by an animation blueprint)Since this instance is transient, it is not safe to be used during construction script |
