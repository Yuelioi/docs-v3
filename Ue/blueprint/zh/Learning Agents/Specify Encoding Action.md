---
display_name: Specify Encoding Action
order: 290
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new encoding action. This represents an action which will be a decoding of another sub-action using a small neural network.

Target is Learning Agents Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Action Schema |
| struct | Element | The sub-action. |
| integer | Encoding Size | The encoding size used to decode this sub-action. |
| integer | Hidden Layer Num | The number of hidden layers used to decode this sub-action. |
| enum | Activation Function | The activation function used to decode this sub-action. |
| name | Tag | The tag of this new action. Used during action object validation and debugging. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created action schema element. |
