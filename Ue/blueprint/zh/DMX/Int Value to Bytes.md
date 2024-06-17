---
title: Int Value to Bytes
order: 57
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [DMX](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DMX)

Return the Bytes format of Value in the desired Signal Format.

Target is DMXSubsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | In Value |  |
| enum | In Signal Format |  |
| boolean | Use LSB | Least Significant Byte mode makes the individual bytes (channels) of the function be interpreted with the first bytes being the lowest part of the number. Most Fixtures use MSB (Most Significant Byte). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| byte | Bytes |  |
