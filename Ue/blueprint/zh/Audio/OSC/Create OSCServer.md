---
display_name: Create OSCServer
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [OSC](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/OSC)

Creates an OSC Server. If ReceiveIPAddress left empty (or '0'),
attempts to use LocalHost IP address. If StartListening set,
immediately begins listening on creation.

Target is OSCManager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Receive IPAddress |  |
| integer | Port |  |
| boolean | Multicast Loopback |  |
| boolean | Start Listening |  |
| string | Server Name |  |
| object | Outer |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Creates an OSC Server. If ReceiveIPAddress left empty (or '0'),attempts to use LocalHost IP address. If StartListening set,immediately begins listening on creation. |
