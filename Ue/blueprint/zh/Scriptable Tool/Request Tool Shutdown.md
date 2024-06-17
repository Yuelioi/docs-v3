---
title: Request Tool Shutdown
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Scriptable Tool](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ScriptableTool)

Request that the active Tool be shut down. The Tool can post this to shut itself down (eg in a Tool where
the interaction paradigm is "click to do something and exit").

Target is Scriptable Interactive Tool

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Accept | if this is an Accept/Cancel Tool, Accept it, otherwise Cancel. Ignored for Complete-type Tools. |
| boolean | Show User Popup Message |  |
| text | User Message |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
