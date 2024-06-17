---
title: Scripted Execute Pipeline
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Interchange](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange) > [Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange/Pipeline_1)

ScriptedExecutePipeline, is call after the translation and before we parse the graph to call the factory.
This is where factory node should be created by the pipeline.
Each factory node represent an unreal asset create that will be create by an interchange factory.
Note: - the FTaskPipeline is calling this function not the virtual one that is call by the default implementation.

Target is Interchange Pipeline Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Base Node Container |  |
| object | Source Datas |  |
| string | Content Base Path |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
