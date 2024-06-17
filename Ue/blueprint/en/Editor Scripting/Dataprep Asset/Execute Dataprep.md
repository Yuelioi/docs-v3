---
title: Execute Dataprep
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Dataprep Asset](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/DataprepAsset_1)

Runs the Dataprep asset's producers, execute its recipe and finally runs the consumer to output the results.

Target is Dataprep Core Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Dataprep Asset Interface | Dataprep asset to run. |
| enum | Log Reporting Method | Chose the way the log from the producers, operations and consumer will be reported (this will only affect the log from dataprep). |
| enum | Progress Reporting Method | The way that the progress updates will be reported. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if successful. |
