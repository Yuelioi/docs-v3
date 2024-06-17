---
title: On Render Finished
order: 143
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Event Dispatchers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EventDispatchers)

Assign a function to this delegate to get notified when each individual job is finished.

THIS WILL ONLY BE CALLED IF USING THE RENDERJOB CONVENIENCE FUNCTION.

Because there can only be one job in the queue when using RenderJob, this will be called when
the render is complete, and the executor has been released. This allows you to queue up another
job immediately as a result of the OnRenderFinished callback.
