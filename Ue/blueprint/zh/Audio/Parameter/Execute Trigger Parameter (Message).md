---
title: Execute Trigger Parameter (Message)
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Parameter](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Parameter)

Executes a named trigger. Does *not* cache trigger value, so only executes if the sound
is already playing. If the intent is for the trigger to execute immediately (if playing)
and be called on initialization for all future instances, call 'SetBoolParameter' with the
intended initial trigger behavior (true if trigger desired on initialization, false if not).

Target is Audio Parameter Controller Interface

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
