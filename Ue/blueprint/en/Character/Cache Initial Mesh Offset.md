---
title: Cache Initial Mesh Offset
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Character](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Character)

Cache mesh offset from capsule. This is used as the target for network smoothing interpolation, when the mesh is offset with lagged smoothing.
This is automatically called during initialization; call this at runtime if you intend to change the default mesh offset from the capsule.
See: GetBaseTranslationOffset(), GetBaseRotationOffset()

Target is Character

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Mesh Relative Location |  |
| rotator | Mesh Relative Rotation |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
