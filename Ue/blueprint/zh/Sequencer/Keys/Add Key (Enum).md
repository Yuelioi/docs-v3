---
title: Add Key (Enum)
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Keys](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Keys)

Add a key to this channel. This initializes a new key and returns a reference to it.

Target is Movie Scene Scripting Byte Channel

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Time | The frame this key should go on. Respects TimeUnit to determine if it is a display rate frame or a tick resolution frame. |
| byte | New Value | The value that this key should be created with. |
| real | Sub Frame | Optional \[0-1) clamped sub-frame to put this key on. Ignored if TimeUnit is set to Tick Resolution. |
| enum | Time Unit | Is the specified InTime in Display Rate frames or Tick Resolution. |
| enum | In Interpolation | Interpolation method the key should use. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The key that was created with the specified values at the specified time. |
