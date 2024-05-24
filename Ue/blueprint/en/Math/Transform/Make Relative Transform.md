---
display_name: Make Relative Transform
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Transform](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Transform)

Computes a relative transform of one transform compared to another.

Example: ChildOffset = MakeRelativeTransform(Child.GetActorTransform(), Parent.GetActorTransform())
This computes the relative transform of the Child from the Parent.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| transform | A | The object's transform |
| transform | Relative To | The transform the result is relative to (in the same space as A) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | The new relative transform |
