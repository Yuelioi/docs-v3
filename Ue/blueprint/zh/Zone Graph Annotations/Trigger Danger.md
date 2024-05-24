---
display_name: Trigger Danger
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Zone Graph Annotations](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ZoneGraphAnnotations)

- Triggers Danger event at specific location.
  \*

Target is Zone Graph Disturbance Annotation BPLibrary

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Instigator | (optional) identifies this event coming from specific Instigator, only one danger will persist per instigator. * |
| vector | Position | Position of the danger. * |
| real | Radius | Radius of the danger. * |
| real | Duration | Duration of the danger. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
