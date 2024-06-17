---
title: Pop Containers from OSC Address
order: 60
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [OSC](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/OSC)

Pops container from ordered array of containers. If NumContainers is greater than or equal to the number of containers in address, returns all containers.

Target is OSCManager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Address |  |
| integer | Num Containers |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Containers | Pops container from ordered array of containers. If NumContainers is greater than or equal to the number of containers in address, returns all containers. |
