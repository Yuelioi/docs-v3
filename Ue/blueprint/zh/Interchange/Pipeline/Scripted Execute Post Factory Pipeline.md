---
display_name: Scripted Execute Post Factory Pipeline
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Interchange](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange) > [Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange/Pipeline_1)

ScriptedExecutePostFactoryPipeline is called after the factory creates an Unreal asset, but before it calls PostEditChange.
Note: - The FTaskPreCompletion task calls this function, not the virtual one that is called by the default implementation.

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
