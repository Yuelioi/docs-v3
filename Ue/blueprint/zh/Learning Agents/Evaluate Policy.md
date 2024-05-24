---
display_name: Evaluate Policy
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Calling this function will run the underlying neural network on the previously encoded observations to populate
the encoded actions. This should be called after EncodeObservations and before DecodeAndSampleActions.

Target is Learning Agents Policy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
