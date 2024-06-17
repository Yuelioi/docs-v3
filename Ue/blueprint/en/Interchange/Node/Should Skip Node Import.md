---
title: Should Skip Node Import
order: 74
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Interchange](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange) > [Node](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange/Node_1)

Return true if this node should skip the factory import process, or false otherwise.
Nodes can be in a situation where we have to skip the import process because we cannot import the associated asset for multiple reasons. For example:

- An asset can already exist and represents a different type (UClass).
- An asset can already exist and is being compiled.
- An asset can already exist and is being imported by another concurrent import task (such as a user importing multiple files at the same time in the same content folder).

Target is Interchange Factory Base Node

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Return true if this node should skip the factory import process, or false otherwise.Nodes can be in a situation where we have to skip the import process because we cannot import the associated asset for multiple reasons. For example:- An asset can already exist and represents a different type (UClass).- An asset can already exist and is being compiled.- An asset can already exist and is being imported by another concurrent import task (such as a user importing multiple files at the same time in the same content folder). |
