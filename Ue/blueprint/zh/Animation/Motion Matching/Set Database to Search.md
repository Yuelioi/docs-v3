---
display_name: Set Database to Search
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Motion Matching](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/MotionMatching)

Set the database to search on the motion matching node. This overrides the Database property on the motion matching node.

Target is Motion Matching Anim Node Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Motion Matching Node | The motion matching node to operate on. |
| object | Database | The database for the motion matching node to search. |
| enum | Interrupt Mode | mode to control the continuing pose search (the current animation that's playing) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
