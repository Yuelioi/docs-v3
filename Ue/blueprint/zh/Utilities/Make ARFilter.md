---
title: Make ARFilter
order: 26
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities)

Builds an ARFilter struct. You should be using ClassPaths and RecursiveClassPathsExclusionSet, ClassNames and RecursiveClassesExclusionSet are deprecated.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| name | Package Names |  |
| name | Package Paths |  |
| struct | Soft Object Paths |  |
| struct | Class Paths |  |
| struct | Recursive Class Paths Exclusion Set |  |
| name | Class Names | \[DEPRECATED\] - Class names are now represented by path names. If non-empty, this input will result in a runtime warning. Please use the ClassPaths input instead. |
| name | Recursive Classes Exclusion Set | \[DEPRECATED\] - Class names are now represented by path names. If non-empty, this input will result in a runtime warning. Please use the RecursiveClassPathsExclusionSet input instead. |
| boolean | Recursive Paths |  |
| boolean | Recursive Classes |  |
| boolean | Include Only on Disk Assets |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value |  |
