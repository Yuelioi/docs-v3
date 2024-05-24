---
display_name: Read Leaderboard Integer
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Online](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online) > [Leaderboard](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online/Leaderboard)

Queries a leaderboard for an integer value

Target is Leaderboard Query Callback Proxy

Latent. This node will complete at a later time. Latent nodes can only be placed in event graphs.

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Player Controller |  |
| name | Stat Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success | Called when there is a successful leaderboard query |
| exec | On Failure | Called when there is an unsuccessful leaderboard query |
| integer | Leaderboard Value |  |
