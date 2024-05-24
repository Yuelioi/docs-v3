---
display_name: On Movie Pipeline Work Finished Delegate
order: 91
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Called when we have completely finished this pipeline. This means that all frames have been rendered,
all files written to disk, and any post-finalize exports have finished. This Pipeline will call
Shutdown() on itself before calling this delegate to ensure we've unregistered from all delegates
and are no longer trying to do anything (even if we still exist).

The params struct in the return will have metadata about files written to disk for each shot.
