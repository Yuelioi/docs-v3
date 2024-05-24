---
display_name: Fill Data Table from CSV File
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Data Table](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/DataTable)

Empty and fill a Data Table from CSV file.

Target is Data Table Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Data Table |  |
| string | CSVFile Path | The file path of the CSV file. |
| object | Import Row Struct | Optional row struct to apply on import. If set will also force the import to run automated (no questions or dialogs). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the operation succeeds, check the log for errors if it didn't succeed. |
