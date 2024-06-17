---
title: Press Key
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Interaction](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interaction)

Press a key as if it had come from the keyboard. Avoid using this for 'a-z|A-Z', things like
the Editable Textbox in Slate expect OnKeyChar to be called to signal a specific character being
send to the widget. So for those cases you should use SendKeyChar.

Target is Widget Interaction Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Key |  |
| boolean | Repeat |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Press a key as if it had come from the keyboard. Avoid using this for 'a-z|A-Z', things likethe Editable Textbox in Slate expect OnKeyChar to be called to signal a specific character beingsend to the widget. So for those cases you should use SendKeyChar. |
