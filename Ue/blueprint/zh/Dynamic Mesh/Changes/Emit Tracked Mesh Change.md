---
title: Emit Tracked Mesh Change
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dynamic Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMesh) > [Changes](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMesh/Changes)

Emit an undo/redo Change for a modified TargetMesh, based on the ChangeTracker information that was
saved (via call to BeginTrackedMeshChange) before TargetMesh was modified. This function must be
called in the context of a Transaction (ie BeginTransaction / EndTransaction pair)

Target is Geometry Script Library Editor Dynamic Mesh Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Change Tracker |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Dynamic Mesh | Emit an undo/redo Change for a modified TargetMesh, based on the ChangeTracker information that wassaved (via call to BeginTrackedMeshChange) before TargetMesh was modified. This function must becalled in the context of a Transaction (ie BeginTransaction / EndTransaction pair) |
