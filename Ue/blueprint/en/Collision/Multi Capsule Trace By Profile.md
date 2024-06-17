---
title: Multi Capsule Trace By Profile
order: 50
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Sweep a capsule against the world and return all initial overlaps using a specific profile, then overlapping hits and then first blocking hit
Results are sorted, so a blocking hit (if found) will be the last element of the array
Only the single closest blocking result will be generated, no tests will be done after that

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Start | Start of line segment. |
| vector | End | End of line segment. |
| real | Radius | Radius of the capsule to sweep |
| real | Half Height | Distance from center of capsule to tip of hemisphere endcap. |
| name | Profile Name | The 'profile' used to determine which components to hit |
| boolean | Trace Complex | True to test against complex collision, false to test against simplified collision. |
| object | Actors to Ignore |  |
| enum | Draw Debug Type |  |
| boolean | Ignore Self |  |
| linearcolor | Trace Color |  |
| linearcolor | Trace Hit Color |  |
| real | Draw Time |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Hits | A list of hits, sorted along the trace from start to finish. The blocking hit will be the last hit, if there was one. |
| boolean | Return Value | True if there was a blocking hit, false otherwise. |
