---
display_name: Set Is Dirty
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline) > [Queue](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline/Queue)

Sets the dirty state of this queue. Generally the queue will correctly track the dirty state; however, there are
situations where a queue may need its dirty state reset (eg, it may be appropriate to reset the dirty state after
a call to CopyFrom(), depending on the use case).

Target is Movie Pipeline Queue

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | New Dirty State |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
