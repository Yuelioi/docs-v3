---
display_name: Copy Material Instance Parameters
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering) > [Material](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering/Material)

Copies over parameters given a material interface (copy each instance following the hierarchy)
Very slow implementation, avoid using at runtime. Hopefully we can replace it later with something like CopyInterpParameters()
The output is the object itself (this). Copying 'quick parameters only' will result in a much
faster copy process but will only copy dynamic scalar, vector and texture parameters on clients.

Target is Material Instance Dynamic

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Source |  |
| boolean | Quick Parameters Only | Copy scalar, vector and texture parameters only. Much faster but may not include required data |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
