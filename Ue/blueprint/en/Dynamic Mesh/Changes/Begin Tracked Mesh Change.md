---
display_name: Begin Tracked Mesh Change
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dynamic Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMesh) > [Changes](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMesh/Changes)

Save current state of TargetMesh so that an undoable/redoable Change can be emitted
after TargetMesh is modified, using EmitTrackedMeshChange().

Target is Geometry Script Library Editor Dynamic Mesh Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Change Tracker | output structure containing initial TargetMesh state |
| object | Dynamic Mesh |  |
