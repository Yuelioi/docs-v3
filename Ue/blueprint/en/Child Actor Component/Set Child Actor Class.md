---
title: Set Child Actor Class
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Child Actor Component](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ChildActorComponent)

Sets the class to use for the child actor.
If called on a template component (owned by a CDO), the properties of any existing child actor template will be copied as best possible to the template.
If called on a component instance in a world (and the class is changing), the created ChildActor will use the class defaults as template.

Target is Child Actor Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | In Class | The Actor subclass to spawn as a child actor |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
