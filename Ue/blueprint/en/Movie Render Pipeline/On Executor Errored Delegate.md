---
display_name: On Executor Errored Delegate
order: 80
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Called when an individual job reports a warning/error. Jobs are considered fatal
if the severity was bad enough to abort the job (missing sequence, write failure, etc.)

Exposed for Blueprints/Python. Called at the same time as the native one.
