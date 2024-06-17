---
title: Make Pulsating Value
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Float](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Float)

Simple function to create a pulsating scalar value

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| real | In Current Time | Current absolute time |
| real | In Pulses Per Second | How many full pulses per second? |
| real | In Phase | Optional phase amount, between 0.0 and 1.0 (to synchronize pulses) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Pulsating value (0.0-1.0) |
