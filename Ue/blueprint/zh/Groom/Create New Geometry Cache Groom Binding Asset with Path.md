---
display_name: Create New Geometry Cache Groom Binding Asset with Path
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Groom](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Groom)

Create a new groom binding asset within the contents space of the project.

Target is Groom Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Desired Package Path | The package path to use for the groom binding |
| object | Groom Asset | Groom asset for binding |
| object | Geometry Cache |  |
| integer | Num Interpolation Points | Number of point used for RBF constraint (if used) |
| object | Source Geometry Cache for Transfer |  |
| integer | Matching Section |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
