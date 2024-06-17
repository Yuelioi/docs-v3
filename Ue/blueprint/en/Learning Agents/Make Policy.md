---
title: Make Policy
order: 215
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Constructs this object to be used with the given agent interactor and policy settings.

Target is Learning Agents Policy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Manager | The input Manager |
| object | In Interactor | The input Interactor component |
| class | Class | The policy class |
| name | Name | The policy name |
| object | Encoder Neural Network Asset | Optional Encoder Network Asset to use. If not provided, asset is empty, or bReinitializeEncoderNetwork is set then a new neural network object will be created. |
| object | Policy Neural Network Asset | Optional Policy Network Asset to use. If not provided, asset is empty, or bReinitializePolicyNetwork is set then a new neural network object will be created according to the given PolicySettings. |
| object | Decoder Neural Network Asset | Optional Decoder Network Asset to use. If not provided, asset is empty, or bReinitializeDecoderNetwork is set then a new neural network object will be created. |
| boolean | Reinitialize Encoder Network | If to reinitialize the encoder network |
| boolean | Reinitialize Policy Network | If to reinitialize the policy network |
| boolean | Reinitialize Decoder Network | If to reinitialize the decoder network |
| struct | Policy Settings | The policy settings to use on creation of a new policy network |
| integer | Seed | Random seed to use for initializing network weights and policy sampling |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
