---
title: Add Actor to Exclude from Hit Tests
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Viewport World Interaction](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ViewportWorldInteraction)

Adds an actor to the list of actors to never allow an interactor to hit in the scene. No selection. No hover.
There's no need to remove actors from this list. They'll expire from it automatically when destroyed.

Target is Viewport World Interaction

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Actor to Exclude from Hit Tests | The actor that should be forever excluded from hit tests |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
