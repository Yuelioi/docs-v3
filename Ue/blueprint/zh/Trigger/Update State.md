---
title: Update State
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Trigger](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Trigger)

This function checks if the requisite conditions have been met for the trigger to fire.
Returns Trigger State None - No trigger conditions have been met. Trigger is inactive.
Trigger State Ongoing - Some trigger conditions have been met. Trigger is processing but not yet active.
Trigger State Triggered - All trigger conditions have been met to fire. Trigger is active.

Target is Input Trigger

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Player Input |  |
| struct | Modified Value |  |
| real | Delta Time |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| enum | Return Value | This function checks if the requisite conditions have been met for the trigger to fire.Returns Trigger State None - No trigger conditions have been met. Trigger is inactive.Trigger State Ongoing - Some trigger conditions have been met. Trigger is processing but not yet active.Trigger State Triggered - All trigger conditions have been met to fire. Trigger is active. |
