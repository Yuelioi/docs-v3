---
display_name: Convert Custom Kernel to Function
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Optimus Node Graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/OptimusNodeGraph)

Takes a custom kernel and converts to a packaged function. If the given node is not a
custom kernel or cannot be converted, a nullptr is returned.

Target is Optimus Node Graph

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Custom Kernel |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Takes a custom kernel and converts to a packaged function. If the given node is not acustom kernel or cannot be converted, a nullptr is returned. |
