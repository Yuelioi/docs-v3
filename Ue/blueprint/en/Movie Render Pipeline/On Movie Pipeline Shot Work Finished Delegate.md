---
display_name: On Movie Pipeline Shot Work Finished Delegate
order: 90
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

This callback will not be called by default due to performance reasons. You need to opt into this (via scripting
in MoviePipeline or in the node in Movie Graph) by setting FlushDiskWritesPerShot to true in the output setting
for this job's configuration.

Called after each shot is finished and files have been flushed to disk. The returned data in
the params struct will have only the per-shot metadata for the just finished shot. Use
OnMoviePipelineWorkFinishedDelegate if you need all of the metadata.
