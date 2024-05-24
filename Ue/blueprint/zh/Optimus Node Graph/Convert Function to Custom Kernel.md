---
display_name: Convert Function to Custom Kernel
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Optimus Node Graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/OptimusNodeGraph)

Takes a kernel function and unpackages to a custom kernel. If the given node is not a
kernel function or cannot be converted, a nullptr is returned.

Target is Optimus Node Graph

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Kernel Function |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Takes a kernel function and unpackages to a custom kernel. If the given node is not akernel function or cannot be converted, a nullptr is returned. |
