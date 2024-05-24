---
display_name: Play Anim And Wait
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Start playing an animation montage on the avatar actor and wait for it to finish
If StopWhenAbilityEnds is true, this montage will be aborted if the ability ends normally. It is always stopped when the ability is explicitly cancelled.
On normal execution, OnBlendOut is called when the montage is blending out, and OnCompleted when it is completely done playing
OnInterrupted is called if another montage overwrites this, and OnCancelled is called if the ability or task is cancelled

Target is Ability Task Play Anim and Wait

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | Task Instance Name | Set to override the name of this task, for later querying |
| object | Anim Sequence |  |
| name | Slot Name |  |
| real | Blend in Time |  |
| real | Blend Out Time |  |
| real | In Play Rate |  |
| real | Start Time Seconds | Starting time offset in montage, this will be overridden by StartSection if that is also set |
| boolean | Stop when Ability Ends | If true, this montage will be aborted if the ability ends normally. It is always stopped when the ability is explicitly cancelled |
| real | Anim Root Motion Translation Scale | Change to modify size of root motion or set to 0 to block it entirely |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Completed |  |
| exec | On Blend Out |  |
| exec | On Blend In |  |
| exec | On Interrupted |  |
| exec | On Cancelled |  |
