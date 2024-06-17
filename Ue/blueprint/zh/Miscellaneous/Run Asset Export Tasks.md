---
title: Run Asset Export Tasks
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Miscellaneous](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Miscellaneous)

Export the given objects to files. Child classes do not override this, but they do provide an Export() function
to do the resource-specific export work.

Target is Exporter

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Export Tasks | The array of tasks to export. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if all tasks ran without error |
