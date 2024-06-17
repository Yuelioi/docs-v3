---
title: Add Labeled Edge
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieGraph)

Add a connection in the graph between the given nodes and pin names. Pin name may be empty for basic
nodes (if no name is displayed in the UI). Can be used for either input or output pins.
Returns False if the pin could not be found, or the connection could not be made (type mismatches).

Target is Movie Graph Config

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | From Node |  |
| name | From Pin Label |  |
| object | To Node |  |
| name | To Pin Label |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Add a connection in the graph between the given nodes and pin names. Pin name may be empty for basicnodes (if no name is displayed in the UI). Can be used for either input or output pins.Returns False if the pin could not be found, or the connection could not be made (type mismatches). |
