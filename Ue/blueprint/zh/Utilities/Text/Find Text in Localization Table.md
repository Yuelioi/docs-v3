---
title: Find Text in Localization Table
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Text](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Text)

Attempts to find existing Text using the representation found in the loc tables for the specified namespace and key.

Target is Kismet Text Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | Namespace | The namespace of the text to find (if any). |
| string | Key | The key of the text to find. |
| string | Source String | If set (not empty) then the found text must also have been created from this source string. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| text | Out Text |  |
| boolean | Return Value |  |
