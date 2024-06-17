---
title: Can Conversation Continue
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Conversation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Conversation)

Checks the provided task result against any which would end the conversation e.g. EConversationTaskResultType::Invalid
or EConversationTaskResultType::AbortConversation

Target is Conversation Context Helpers

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Conversation Tas Result |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Checks the provided task result against any which would end the conversation e.g. EConversationTaskResultType::Invalidor EConversationTaskResultType::AbortConversation |
