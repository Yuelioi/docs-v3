---
title: Set Animation Mode
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/Animation)

Set the Animation Mode

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| enum | In Animation Mode | : Requested AnimationMode |
| boolean | Force Init Anim Script Instance | : Init AnimScriptInstance if the AnimationMode is AnimationBlueprint even if the new animation mode is the same as current (this allows to use BP construction script to do this) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
