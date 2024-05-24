---
display_name: Assert Equal (Rotator Orientation)
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asserts](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Asserts)

Assert that the orientation of two rotators is the same within a small tolerance. Robust to quaternion singularities where angles can differ despite having an identical orientation.

Target is Functional Test

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| rotator | Actual |  |
| rotator | Expected |  |
| string | What | A name to use in the message if the assert fails ("Expected 'What' to be {Expected} but it was {Actual} for context ''") |
| real | Tolerance |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value |  |
