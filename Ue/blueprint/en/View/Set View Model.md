---
title: Set View Model
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [View](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/View)

Set the viewmodel of the specified name.
The viewmodel needs to be settable and the type should match (child of the defined viewmodel).
If the view is initialized, all bindings that uses that viewmodel will be re-executed with the new viewmodel instance.

Target is MVVM View

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | View Model Name |  |
| interface | View Model |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Set the viewmodel of the specified name.The viewmodel needs to be settable and the type should match (child of the defined viewmodel).If the view is initialized, all bindings that uses that viewmodel will be re-executed with the new viewmodel instance. |
