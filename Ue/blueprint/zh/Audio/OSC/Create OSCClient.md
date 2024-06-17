---
title: Create OSCClient
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [OSC](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/OSC)

Creates an OSC Client. If SendIPAddress left empty (or '0'), attempts to use
attempts to use LocalHost IP address.

Target is OSCManager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Send IPAddress |  |
| integer | Port |  |
| string | Client Name |  |
| object | Outer |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Creates an OSC Client. If SendIPAddress left empty (or '0'), attempts to useattempts to use LocalHost IP address. |
