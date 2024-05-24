---
display_name: Make Trainer
order: 243
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Constructs the trainer and runs the setup functions for rewards and completions.

Target is Learning Agents Trainer

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Manager | The agent manager we are using. |
| object | In Interactor | The agent interactor we are training with. |
| object | In Policy | The policy to be trained. |
| object | In Critic | The critic to be trained. |
| class | Class | The trainer class |
| name | Name | The trainer name |
| struct | Trainer Settings | The trainer settings to use. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
