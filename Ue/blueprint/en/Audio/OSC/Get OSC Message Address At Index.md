---
display_name: Get OSC Message Address At Index
order: 33
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [OSC](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/OSC)

Sets Value to address at provided Index in OSCMessage if in bounds and OSC type matches 'String' (Does NOT return address of message, rather
string packed in message and casts to OSC address). Returns if string found at index and is valid OSC address path.

Target is OSCManager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Message |  |
| integer | Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Value |  |
| boolean | Succeeded | Sets Value to address at provided Index in OSCMessage if in bounds and OSC type matches 'String' (Does NOT return address of message, ratherstring packed in message and casts to OSC address). Returns if string found at index and is valid OSC address path. |
