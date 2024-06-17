---
title: Prestream Mesh LODs
order: 68
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering)

Tell the streaming system to start streaming in all LODs for the mesh.
Note: this function may set bIgnoreStreamingMipBias on this component enable the FastForceResident system.

Target is Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Seconds | Number of seconds to force all LODs to be resident |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | bool True if streaming was successfully requested |
