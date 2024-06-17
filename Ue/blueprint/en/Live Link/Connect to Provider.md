---
title: Connect to Provider
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Live Link](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LiveLink)

- Connects to a given Message Bus Provider and returns a handle to the created LiveLink Source

Target is Live Link Message Bus Finder

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Provider | The provider to connect to. * |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Source Handle | A handle to the created LiveLink Source, lets you query information about the created source and request a shutdown |
