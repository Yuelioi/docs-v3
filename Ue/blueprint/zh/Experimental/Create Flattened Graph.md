---
display_name: Create Flattened Graph
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Experimental](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Experimental)

Given a user-defined evaluation context, evaluate the graph and build a "flattened" list of settings for each branch discovered.
If there was an error while evaluating the graph, nullptr will be returned and OutError will be populated with a description of the problem.

Target is Movie Graph Config

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Context |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Out Error |  |
| object | Return Value | Given a user-defined evaluation context, evaluate the graph and build a "flattened" list of settings for each branch discovered.If there was an error while evaluating the graph, nullptr will be returned and OutError will be populated with a description of the problem. |
