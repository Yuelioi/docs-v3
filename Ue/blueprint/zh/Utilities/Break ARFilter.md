---
title: Break ARFilter
order: 31
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities)

Breaks an ARFilter struct into its component pieces. You should be using ClassPaths and RecursiveClassPathsExclusionSet from this node, ClassNames and RecursiveClassesExclusionSet are deprecated.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | In ARFilter |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| name | Package Names |  |
| name | Package Paths |  |
| struct | Soft Object Paths |  |
| struct | Class Paths |  |
| struct | Recursive Class Paths Exclusion Set |  |
| name | Class Names | \[DEPRECATED\] - Class names are now represented by path names. Please use the ClassPaths output instead. |
| name | Recursive Classes Exclusion Set | \[DEPRECATED\] - Class names are now represented by path names. Please use the RecursiveClassPathsExclusionSet output instead. |
| boolean | Recursive Paths |  |
| boolean | Recursive Classes |  |
| boolean | Include Only on Disk Assets |  |
