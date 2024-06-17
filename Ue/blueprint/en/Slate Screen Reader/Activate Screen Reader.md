---
title: Activate Screen Reader
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Slate Screen Reader](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SlateScreenReader)

Activates the underlying screen reader. Use this to allow screen reader users to register with the screen reader
and receive accessible feedback via text to speech and get access to other screen reader services.
A basic workflow with activation would be:
ActivateScreenReader() -> RegisterScreenReaderUser() -> ActivateScreenReaderUser()
See: RegisterScreenReaderUser(), ActivateScreenReaderUser()

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
