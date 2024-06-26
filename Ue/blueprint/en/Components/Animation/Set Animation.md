---
title: Set Animation
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/Animation)

Animation play functions
\*

- These changes status of animation instance, which is transient data, which means it won't serialize with this component
- Because of that reason, it is not safe to be used during construction script
- Please use OverrideAnimationData for construction script. That will override AnimationData to be serialized

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | New Anim to Play |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
