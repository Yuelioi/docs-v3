---
display_name: Find Recursive
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [File Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/FileUtils)

Finds all the files and/or directories within the given directory and any sub-directories. Files can be found with anoptional file extension filter.

Target is Blueprint File Utils BPLibrary

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Start Directory | The absolute path to the directory to start the search. Ex: "C:\\UnrealEditor\\Pictures" |
| string | Wildcard | Wildcard that can be used to find files or directories with specific text in their name. E.g *.png to find all files ending with the png extension,* images\* to find anything with the word "images" in it Otherwise FileExtension can be of the form .EXT or just EXT and only files with that extension will be returned. Does not apply to directories |
| boolean | Find Files | Whether or not to find files |
| boolean | Find Directories | Whether or not to find directories |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Found Paths | All the paths (directories and/or files) found |
| boolean | Return Value | true if anything was found, false otherwise |
