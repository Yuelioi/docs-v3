---
title: Get Distance Between Two Sockets
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Utilities)

Computes the distance between two bones / sockets and can remap the range.

Target is Kismet Animation Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Component | The skeletal component to look for the sockets / bones within |
| name | Socket or Bone Name A | The name of the first socket / bone |
| enum | Socket Space A | The space for the first socket / bone |
| name | Socket or Bone Name B | The name of the second socket / bone |
| enum | Socket Space B | The space for the second socket / bone |
| boolean | Remap Range | If set to true, the distance will be remapped using the range parameters |
| real | In Range Min | The minimum for the input range (commonly == 0.0) |
| real | In Range Max | The maximum for the input range (the max expected distance) |
| real | Out Range Min | The minimum for the output range (commonly == 0.0) |
| real | Out Range Max | The maximum for the output range (commonly == 1.0) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value |  |
