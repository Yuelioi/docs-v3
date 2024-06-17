---
title: Assert Equal (Vector)
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asserts](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Asserts)

Assert that two vectors are (memberwise) equal within a small tolerance.

Target is Functional Test

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Actual |  |
| vector | Expected |  |
| string | What | A name to use in the message if the assert fails ("Expected 'What' to be {Expected} but it was {Actual} for context ''") |
| real | Tolerance |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value |  |
