---
display_name: Get Project Root Asset Directory
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Asset](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Asset_1)

Historically, all project assets were stored in the logical "/Game/" directory
when using plugins or UEFN projects, we want to ease asset reuse, and so the ambiguous
"/Game/" directory is untenable. This function will return the useful project name.

Target is Editor Asset Library

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | The current project name in UEFN, otherwise /Game/ for .uprojects |
