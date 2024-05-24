---
display_name: Actions Import
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Menu Actions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/MenuActions)

Imports the currently opened USD Stage into persistent UE assets, actors and components on the level.
Corresponds to the "Actions -> Import" action on the USD Stage Editor menu bar.

Target is Usd Stage Editor Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Output Content Folder | Content path (e.g. "/Game/Imports") to receive the imported assets. If this path is the empty string a dialog will be shown to let the user pick the folder. |
| object | Options |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
