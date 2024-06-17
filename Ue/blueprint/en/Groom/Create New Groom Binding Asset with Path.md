---
title: Create New Groom Binding Asset with Path
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Groom](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Groom)

Create a new groom binding asset within the contents space of the project.

Target is Groom Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | In Desired Package Path | The package path to use for the groom binding |
| object | In Groom Asset | Groom asset for binding |
| object | In Skeletal Mesh | Skeletal mesh on which the groom should be bound to |
| integer | In Num Interpolation Points | Number of point used for RBF constraint (if used) |
| object | In Source Skeletal Mesh for Transfer | Skeletal mesh on which the groom was authored. This should be used only if the skeletal mesh on which the groom is attached to, does not match the rest pose of the groom |
| integer | In Matching Section |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
