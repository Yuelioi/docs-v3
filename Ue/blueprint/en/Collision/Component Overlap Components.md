---
title: Component Overlap Components
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Returns an array of components that overlap the given component.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Component | Component to test with. |
| transform | Component Transform | Defines where to place the component for overlap testing. |
| enum | Object Types |  |
| class | Component Class Filter |  |
| object | Actors to Ignore | Ignore these actors in the list |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Components |  |
| boolean | Return Value | true if there was an overlap that passed the filters, false otherwise. |
