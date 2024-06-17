---
title: Convert Object Path (String) to OSC Address
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [OSC](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/OSC)

Converts object path string to OSC Address, converting folders to address containers and the object's name to the address method.
Only supports parent objects (See UObjectBaseUtility::GetPathName and UObjectBaseUtility::GetFullName).

Target is OSCManager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Path Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Address | Converts object path string to OSC Address, converting folders to address containers and the object's name to the address method.Only supports parent objects (See UObjectBaseUtility::GetPathName and UObjectBaseUtility::GetFullName). |
