---
title: Apply Internal Strain
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Chaos Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ChaosPhysics)

Apply an internal strain to specific piece of the geometry collection

Target is Geometry Collection Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Item Index | item index ( from HitResult) of the piece to apply strain on |
| vector | Location | world location of where to apply the strain |
| real | Radius | radius from the location point to apply the strain to ( using the center of mass of the pieces ) |
| integer | Propagation Depth | How many level of connection to follow to propagate the strain through |
| real | Propagation Factor | when using propagation, the factor to multiply the strain from one level to the other, allowing falloff effect |
| real | Strain | strain / damage to apply |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
