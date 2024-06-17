---
title: Montage Sync Follow
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Montage](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Montage)

Synchronize a montage to another anim instance's montage. Both montages must be playing already

Target is Anim Instance

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Montage Follower | : The montage that will follow the leader in OtherAnimInstance |
| object | Other Anim Instance | : The other anim instance we want to synchronize to. Can be set to self |
| object | Montage Leader | : The montage we want to follow in the other anim instance |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
