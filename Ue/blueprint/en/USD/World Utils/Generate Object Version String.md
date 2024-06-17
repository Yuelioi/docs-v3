---
title: Generate Object Version String
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [World Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/WorldUtils)

Generates a unique identifier string that involves ObjectToExport's package's persistent guid, the
corresponding file save date and time, and the number of times the package has been dirtied since last being
saved.
Optionally it can also combine that hash with a hash of the export options being used for the export, if
available.
This can be used to track the version of exported assets and levels, to prevent reexporting of actors and
components.

Target is Usd Conversion Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Object to Export |  |
| object | Export Options |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Return Value | Generates a unique identifier string that involves ObjectToExport's package's persistent guid, thecorresponding file save date and time, and the number of times the package has been dirtied since last beingsaved.Optionally it can also combine that hash with a hash of the export options being used for the export, ifavailable.This can be used to track the version of exported assets and levels, to prevent reexporting of actors andcomponents. |
