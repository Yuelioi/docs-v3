---
title: Get All Referenced Asset Datas (Message)
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Typed Element Interfaces](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementInterfaces) > [Asset Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementInterfaces/AssetData)

Returns any asset datas for content objects referenced by handle.
If the given handle itself has valid asset data, it should be returned as the last element of the array.

Target is Typed Element Asset Data Interface

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Element Handle |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | An array of valid asset datas. |
