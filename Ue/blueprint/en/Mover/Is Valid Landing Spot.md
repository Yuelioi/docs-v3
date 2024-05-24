---
display_name: Is Valid Landing Spot
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mover](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mover)

Checks if a hit result represents a walkable location that an actor can land on

Target is Air Movement Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Updated Component |  |
| object | Updated Primitive |  |
| vector | Location |  |
| struct | Hit |  |
| real | Floor Sweep Distance |  |
| real | Max Walk Slope Cosine |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Floor Result |  |
| boolean | Return Value | Checks if a hit result represents a walkable location that an actor can land on |
