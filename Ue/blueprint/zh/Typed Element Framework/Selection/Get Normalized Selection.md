---
title: Get Normalized Selection
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Typed Element Framework](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementFramework) > [Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementFramework/Selection)

Get a normalized version of this selection set that can be used to perform operations like gizmo manipulation, deletion, copying, etc.
This will do things like expand out groups, and resolve any parent\<->child elements so that duplication operations aren't performed on both the parent and the child.

Target is Typed Element Selection Set Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Selection Set |  |
| struct | Normalization Options |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Get a normalized version of this selection set that can be used to perform operations like gizmo manipulation, deletion, copying, etc.This will do things like expand out groups, and resolve any parent\<->child elements so that duplication operations aren't performed on both the parent and the child. |
