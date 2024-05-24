---
display_name: Deactivate Screen Reader
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Slate Screen Reader](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SlateScreenReader)

Deactivates the underlying screen reader and prevents screen reader users from getting
any accessible feedback via text to speech or using any other screen reader services.
Note: When the screen reader is deactivated, none of the registered screen reader users will be unregistered or cleared. This allows you to
deactivate the screen reader to prevent accessible services such as text to speech from triggering and then activate the screen reader again to continue those services.

Target is Slate Screen Reader Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
