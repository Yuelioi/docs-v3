---
display_name: Cancel
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Render Grid Queue](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RenderGridQueue)

Cancels the current and the remaining queued jobs. Relies on the internal movie pipeline implementation of job canceling on whether this will stop the current render grid job from rendering or not. Will always prevent new render grid jobs from rendering.

Target is Render Grid Queue

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
