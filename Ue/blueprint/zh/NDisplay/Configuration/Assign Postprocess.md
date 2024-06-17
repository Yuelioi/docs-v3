---
title: Assign Postprocess
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [NDisplay](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NDisplay) > [Configuration](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NDisplay/Configuration)

Update\\Create node postprocess

Target is Display Cluster Configuration Data

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Node Id |  |
| string | Postprocess Id | Unique postprocess name |
| string | Type | Postprocess type id |
| string | Parameters | Postprocess parameters |
| integer | Order | Control the rendering order of post-processing. Larger value is displayed last |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true, if success |
