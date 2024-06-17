---
title: TrackedActorLabel
order: 123
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [Enhanced Action Events](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/EnhancedActionEvents)

Event for when 'InputAction /VirtualCamera/Modifiers/LensModifier/Inputs/TrackedActorLabel.TrackedActorLabel' triggers.

Note: This is not guaranteed to fire every frame, only when the Action is triggered and the current Input Mode includes 'Game'.

Tip: Use the 'showdebug enhancedinput' command while playing to see debug information about Enhanced Input.

You can change what execution pins are visible by default in the Enhanced Input Editor Preferences.

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Triggered | Triggering occurred after one or more processing ticks |
| exec | Started | An event has occurred that has begun Trigger evaluation. Note: Triggered may also occur this frame, but this event will always be fired first. |
| exec | Ongoing | Triggering is still being processed. For example, an action with a "Press and Hold" triggerwill be "Ongoing" while the user is holding down the key but the time threshold has not been met yet. |
| exec | Canceled | Triggering has been canceled. For example, the user has let go of a key before the "Press and Hold" time threshold.The action has started to be evaluated, but never completed. |
| exec | Completed | The trigger state has transitioned from Triggered to None this frame, i.e. Triggering has finished.Note: Using this event restricts you to one set of triggers for Started/Completed events. You may prefer two actions, each with its own trigger rules.Completed will not fire if any trigger reports Ongoing on the same frame, but both should fire. e.g. Tick 2 of Hold (= Ongoing) + Pressed (= None) combo will raise Ongoing event only. |
| real | Action Value |  |
| real | Elapsed Seconds |  |
| real | Triggered Seconds |  |
| object | Input Action | The input action that caused this event to fire |
