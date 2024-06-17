---
title: Is Locally Viewed
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Pawn](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Pawn)

Is this pawn the ViewTarget of a local PlayerController? Helpful for determining whether the pawn is
visible/critical for any VFX. NOTE: Technically there may be some cases where locally controlled pawns return
false for this, such as if you are using a remote camera view of some sort. But generally it will be true for
locally controlled pawns, and it will always be true for pawns that are being spectated in-game or in Replays.

Target is Pawn

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Is this pawn the ViewTarget of a local PlayerController? Helpful for determining whether the pawn isvisible/critical for any VFX. NOTE: Technically there may be some cases where locally controlled pawns returnfalse for this, such as if you are using a remote camera view of some sort. But generally it will be true forlocally controlled pawns, and it will always be true for pawns that are being spectated in-game or in Replays. |
