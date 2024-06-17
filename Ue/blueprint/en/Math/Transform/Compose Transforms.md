---
title: Compose Transforms
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Transform](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Transform)

Compose two transforms in order: A * B.

Order matters when composing transforms:
A * B will yield a transform that logically first applies A then B to any subsequent transformation.

Example: LocalToWorld = ComposeTransforms(DeltaRotation, LocalToWorld) will change rotation in local space by DeltaRotation.
Example: LocalToWorld = ComposeTransforms(LocalToWorld, DeltaRotation) will change rotation in world space by DeltaRotation.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| transform | A |  |
| transform | B |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | New transform: A * B |
