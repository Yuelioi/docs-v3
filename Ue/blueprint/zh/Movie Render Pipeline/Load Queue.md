---
title: Load Queue
order: 78
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Loads a new queue by copying it into the queue subsystem's current transient queue (the one returned by GetQueue()).

If bPromptOnReplacingDirtyQueue is true and the current queue has been modified since being loaded, a dialog will prompt the
user if they want to discard their changes. If this dialog is rejected, or there was an error loading the queue, returns
false, else returns true. Note that bPromptOnReplacingDirtyQueue is effectively ignored if the application is in
"unattended" mode because the dialog is auto-accepted.

Target is Movie Pipeline Queue Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | Queue to Load |  |
| boolean | Prompt on Replacing Dirty Queue |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Loads a new queue by copying it into the queue subsystem's current transient queue (the one returned by GetQueue()).If bPromptOnReplacingDirtyQueue is true and the current queue has been modified since being loaded, a dialog will prompt theuser if they want to discard their changes. If this dialog is rejected, or there was an error loading the queue, returnsfalse, else returns true. Note that bPromptOnReplacingDirtyQueue is effectively ignored if the application is in"unattended" mode because the dialog is auto-accepted. |
