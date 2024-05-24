---
display_name: Request Refresh
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [List View Base](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ListViewBase)

Sets the list to refresh on the next tick.

Note that refreshing, from a list perspective, is limited to accounting for discrepancies between items and entries.
In other words, it will only release entries that no longer have items and generate entries for new items (or newly visible items).

It does NOT account for changes within existing items - that is up to the item to announce and an entry to listen to as needed.
This can be onerous to set up for simple cases, so it's also reasonable (though not ideal) to call RegenerateAllEntries when changes within N list items need to be reflected.

Target is List View Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
