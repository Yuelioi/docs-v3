---
title: Run Asset Export Task
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Miscellaneous](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Miscellaneous)

Export the given object to file. Child classes do not override this, but they do provide an Export() function
to do the resource-specific export work.

Target is Exporter

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Task | The task to export. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the the object was successfully exported |
