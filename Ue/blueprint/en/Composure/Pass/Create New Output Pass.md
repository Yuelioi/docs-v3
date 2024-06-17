---
title: Create New Output Pass
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Composure](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Composure) > [Pass](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Composure/Pass)

Create a new Output pass into the public list which directly shows in the editor.

Target is Empty Comp Shot

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Pass Name | The name for the new pass. |
| class | Output Type | The class type of the created pass. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | CompositingElementOutput The newly created output pass object. |
