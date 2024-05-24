---
display_name: Create New Transform Pass
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Composure](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Composure) > [Pass](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Composure/Pass)

Create a new Transform pass into the public list which directly shows in the editor.

Target is Empty Comp Shot

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Pass Name | The name for the new pass. |
| class | Transform Type | The class type of the created pass. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | CompositingElementTransform The newly created transform pass object. |
