---
display_name: Create New Groom Binding Asset
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Groom](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Groom)

Create a new groom binding asset within the contents space of the project. The asset name will be auto generated based on the groom asset name and the skeletal asset name

Target is Groom Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Groom Asset | Groom asset for binding |
| object | In Skeletal Mesh | Skeletal mesh on which the groom should be bound to |
| integer | In Num Interpolation Points | (Optional) Number of point used for RBF constraint |
| object | In Source Skeletal Mesh for Transfer | (Optional) Skeletal mesh on which the groom was authored. This should be used only if the skeletal mesh on which the groom is attached to, does not match the rest pose of the groom |
| integer | In Matching Section |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
