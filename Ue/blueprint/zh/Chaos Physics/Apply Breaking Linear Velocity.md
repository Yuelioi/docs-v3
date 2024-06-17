---
title: Apply Breaking Linear Velocity
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Chaos Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ChaosPhysics)

Apply linear velocity on breaking pieces for a specific cluster
If ItemIndex does not represent a cluster this will do nothing

Target is Geometry Collection Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Item Index | item index ( from HitResult) of the cluster owning the breaking pieces to apply velocity on |
| vector | Linear Velocity | linear velocity to apply |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
