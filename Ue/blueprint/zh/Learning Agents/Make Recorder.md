---
title: Make Recorder
order: 218
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Constructs this object and runs the setup functions for the underlying data storage.

Target is Learning Agents Recorder

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Manager | The agent manager we are using. |
| object | In Interactor | The agent interactor we are recording with. |
| class | Class | The recorder class |
| name | Name | The recorder class |
| struct | Recorder Path Settings | The path settings used by the recorder. |
| object | Recording Asset | Optional recording asset to use. If not provided or bReinitializeRecording is set then a new recording object will be created. |
| boolean | Reinitialize Recording |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
