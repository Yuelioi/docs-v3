---
display_name: Get Keep Python Script Alive
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Python](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Python)

Returns the value of the bKeepPythonScriptAlive flag.

If this is false (default), it will close the editor during the next tick (when executing a Python script in the editor-environment using the UnrealEditor-Cmd commandline tool).
If this is true, it will not close the editor by itself, and you will have to close it manually, either by setting this value to false again, or by calling a function like unreal.SystemLibrary.quit_editor().

Target is Editor Python Scripting Library

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | The current value of the bKeepPythonScriptAlive flag. |
