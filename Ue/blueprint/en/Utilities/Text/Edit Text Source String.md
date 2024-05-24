---
display_name: Edit Text Source String
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Text](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Text)

Edit the source string of the given text property, akin to what happens when editing a text property in a details panel.
This will attempt to preserve the existing ID of the text property being edited, or failing that will attempt to build a deterministic ID based on the object and property info.

Note: This is an ADVANCED function that is ONLY safe to be used in environments where the modified text property will be gathered for localization (eg, in the editor, or a game mode that collects text properties to be localized).

Target is Kismet Text Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Text Owner | The object that owns the given Text to be edited. |
| text | Text | The text property to edit. This must be a property that exists on TextOwner. |
| string | Source String | The source string that the edited text property should use. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if edit was possible, or false if not. |
