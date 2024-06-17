---
title: Promote Element
order: 38
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Typed Element Interfaces](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementInterfaces) > [World](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementInterfaces/World)

Promote an element when possible
Generally available when the element is a lighter representation of another element.
Like an instance for example.

Target is Typed Element World Interface

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| struct | In Element Handle |  |
| object | Override World | Override the world in which the promotion might create new elements. Leave it to null to use the world from the handle. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value |  |
