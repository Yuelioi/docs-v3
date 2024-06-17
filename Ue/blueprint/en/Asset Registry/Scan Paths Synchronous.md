---
title: Scan Paths Synchronous
order: 47
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetRegistry)

Scan the supplied paths recursively right now and populate the asset registry. If bForceRescan is true, the paths will be scanned again, even if they were previously scanned

Target is Asset Registry

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| string | In Paths |  |
| boolean | Force Rescan |  |
| boolean | Ignore Deny List Scan Filters |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
