---
display_name: Find Event Graph
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Blueprint Upgrade Tools](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/BlueprintUpgradeTools)

Finds the event graph of the given blueprint. Null if it doesn't have one. This will only return
the primary event graph of the blueprint (the graph named "EventGraph").

Target is Blueprint Editor Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Blueprint | Blueprint to search for the event graph on |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | UEdGraph\* Event graph of the blueprint if it has one, null if it doesn't have one |
