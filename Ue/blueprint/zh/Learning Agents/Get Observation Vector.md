---
title: Get Observation Vector
order: 96
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Get the Observation Vector associated with a particular step of a given recording

Target is Learning Agents Recording

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Record | Index of the record in the array of records. |
| integer | Step | Step of the recording |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Out Observation Vector | Output Observation Vector |
| integer | Out Observation Compatibility Hash | Output Compatibility Hash for the given Observation Vector |
