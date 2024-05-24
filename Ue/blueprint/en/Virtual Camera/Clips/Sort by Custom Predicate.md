---
display_name: Sort by Custom Predicate
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Virtual Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera) > [Clips](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera/Clips)

Sorts the assets based on a custom Blueprint delegate.

Target is Asset Filtering and Sorting Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Assets |  |
| delegate | Sorting Predicate | Implements a Left \<= Right relation |
| enum | Sort Order |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
