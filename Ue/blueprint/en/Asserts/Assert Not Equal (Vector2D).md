---
display_name: Assert Not Equal (Vector2D)
order: 29
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asserts](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Asserts)

Assert that two two-component vectors are (memberwise) not equal within a small tolerance.

Target is Functional Test

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector2d struct | Actual |  |
| vector2d struct | Not Expected |  |
| string | What | A name to use in the message if the assert fails ("Expected 'What' not to be {Expected} but it was {Actual} for context ''") |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value |  |
