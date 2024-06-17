---
title: Play World Camera Shake
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Camera)

Plays an in-world camera shake that affects all nearby local players, with distance-based attenuation. Does not replicate.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| class | Shake | Camera shake asset to use |
| vector | Epicenter | location to place the effect in world space |
| real | Inner Radius | Cameras inside this radius are ignored |
| real | Outer Radius | Cameras outside of InnerRadius and inside this are effected |
| real | Falloff | Affects falloff of effect as it nears OuterRadius |
| boolean | Orient Shake Towards Epicenter | Changes the rotation of shake to point towards epicenter instead of forward |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
