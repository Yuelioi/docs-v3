---
title: Scripted Execute Post Import Pipeline
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Interchange](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange) > [Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange/Pipeline_1)

ScriptedExecutePostImportPipeline is called after an asset is completely imported, after PostEditChange has already been called.
This can be useful if you need build data for one asset to finish setting up another asset.
@example - A PhysicsAsset needs skeletal mesh render data to be built properly.
Note: - the FTaskPostImport calls this function not the virtual one that is call by the default implementation.

Target is Interchange Pipeline Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Base Node Container |  |
| string | Factory Node Key |  |
| object | Created Asset |  |
| boolean | Is AReimport |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
