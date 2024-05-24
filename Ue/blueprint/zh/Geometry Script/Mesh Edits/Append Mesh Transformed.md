---
display_name: Append Mesh Transformed
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Edits](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshEdits)

For each transform in AppendTransforms, apply the transform to AppendMesh and then add its geometry to the TargetMesh.

Target is Geometry Script Library Mesh Basic Edit Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| object | Append Mesh |  |
| transform | Append Transforms |  |
| transform | Constant Transform | the Constant transform will be applied after each Append transform |
| boolean | Constant Transform Is Relative | if true, the Constant transform is applied "in the frame" of the Append Transform, otherwise it is applied as a second transform in local coordinates (ie rotate around the AppendTransform X axis, vs around the local X axis) |
| boolean | Defer Change Notifications |  |
| struct | Append Options | Control how details like mesh attributes are handled when one mesh is appended to another |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |
