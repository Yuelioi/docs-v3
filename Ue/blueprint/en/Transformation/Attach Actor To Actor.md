---
title: Attach Actor To Actor
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Transformation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Transformation)

Attaches the RootComponent of this Actor to the supplied actor, optionally at a named socket.

Target is Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Parent Actor | Actor to attach this actor's RootComponent to |
| name | Socket Name | Socket name to attach to, if any |
| enum | Location Rule | How to handle translation when attaching. |
| enum | Rotation Rule | How to handle rotation when attaching. |
| enum | Scale Rule | How to handle scale when attaching. |
| boolean | Weld Simulated Bodies | Whether to weld together simulated physics bodies.This transfers the shapes in the welded object into the parent (if simulated), which can result in permanent changes that persist even after subsequently detaching. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether the attachment was successful or not |
