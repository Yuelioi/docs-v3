---
title: Get Child Elements (Message)
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Typed Element Interfaces](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementInterfaces) > [Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementInterfaces/Hierarchy)

Get the logical children of this element, if any.
eg) An actor might return its component, or an ISM component might return its static mesh instances.

Note: Appends to OutElementHandles.

Target is Typed Element Hierarchy Interface

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Element Handle |  |
| boolean | Allow Create |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Element Handles |  |
