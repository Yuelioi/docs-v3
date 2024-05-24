---
display_name: Export Static Mesh to PFM file
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [PFMExporter](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PFMExporter)

Generate PFM file from static mesh.
The UV channel must be defined, assigned range 0..1 used as screen surface.
Origin assigned by function arg, or by default used mesh parent.

Target is PFMExporter APIImpl

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Src Mesh | Static mesh with assigned UV channel, used as export source of PFM file |
| object | Origin | (Optional) Custom cave origin node, if not defined, used SrcMesh parent |
| integer | Width | Output PFM mesh texture width |
| integer | Height | Output PFM mesh texture height |
| string | File Name | Output PFM file name |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true, if success |
