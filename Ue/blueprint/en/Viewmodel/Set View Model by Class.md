---
display_name: Set View Model by Class
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Viewmodel](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Viewmodel)

Set the first viewmodel matching the exact specified type. If none is found, set the first viewmodel matching a child of the specified type
The viewmodel needs to be settable and it should have a valid name.
If the view is initialized, all bindings that uses that viewmodel will be re-executed with the new viewmodel instance.

Target is MVVM View

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| interface | New Value |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Set the first viewmodel matching the exact specified type. If none is found, set the first viewmodel matching a child of the specified typeThe viewmodel needs to be settable and it should have a valid name.If the view is initialized, all bindings that uses that viewmodel will be re-executed with the new viewmodel instance. |
