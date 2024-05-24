---
display_name: Add Query
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Settings](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Settings)

Adds a new condition group query to the condition group and returns a ptr to it. The condition group owns the
created query. By default the query is added to the end, but an optional index can be provided if the query
should be placed in a specific location among the existing queries.

Target is Movie Graph Condition Group

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | In Query Type |  |
| integer | Insert Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Adds a new condition group query to the condition group and returns a ptr to it. The condition group owns thecreated query. By default the query is added to the end, but an optional index can be provided if the queryshould be placed in a specific location among the existing queries. |
