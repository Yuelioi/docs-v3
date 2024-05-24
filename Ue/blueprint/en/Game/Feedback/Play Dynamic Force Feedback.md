---
display_name: Play Dynamic Force Feedback
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game) > [Feedback](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game/Feedback)

Latent action that controls the playing of force feedback
Begins playing when Start is called. Calling Update or Stop if the feedback is not active will have no effect.
Completed will execute when Stop is called or the duration ends.
When Update is called the Intensity, Duration, and affect values will be updated with the current inputs

Target is Player Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Start |  |
| exec | Update |  |
| exec | Stop |  |
| object | Target |  |
| real | Intensity | How strong the feedback should be. Valid values are between 0.0 and 1.0 |
| real | Duration | How long the feedback should play for. If the value is negative it will play until stopped |
| boolean | Affects Left Large | Whether the intensity should be applied to the large left servo |
| boolean | Affects Left Small | Whether the intensity should be applied to the small left servo |
| boolean | Affects Right Large | Whether the intensity should be applied to the large right servo |
| boolean | Affects Right Small | Whether the intensity should be applied to the small right servo |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Completed |  |
