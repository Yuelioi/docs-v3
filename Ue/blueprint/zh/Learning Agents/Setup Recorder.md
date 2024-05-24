---
display_name: Setup Recorder
order: 272
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Initializes this object and runs the setup functions for the underlying data storage.

Target is Learning Agents Recorder

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Manager | The agent manager we are using. |
| object | In Interactor | The agent interactor we are recording with. |
| struct | Recorder Path Settings | The path settings used by the recorder. |
| object | Recording Asset | Optional recording asset to use. If not provided or bReinitializeRecording is set then a new recording object will be created. |
| boolean | Reinitialize Recording |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
