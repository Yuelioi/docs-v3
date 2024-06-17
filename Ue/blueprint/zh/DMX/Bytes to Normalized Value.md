---
title: Bytes to Normalized Value
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [DMX](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DMX)

Return normalized value given an array of bytes. Up to the first 4 bytes in the array will be used for the conversion.

Target is DMXSubsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| byte | Bytes |  |
| boolean | Use LSB | Least Significant Byte mode makes the individual bytes (channels) of the function be interpreted with the first bytes being the lowest part of the number. Most Fixtures use MSB (Most Significant Byte). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value |  |
