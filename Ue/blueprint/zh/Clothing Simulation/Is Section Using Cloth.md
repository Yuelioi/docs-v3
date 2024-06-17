---
title: Is Section Using Cloth
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Clothing Simulation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ClothingSimulation)

Checks whether the provided section is using APEX cloth. if bCheckCorrespondingSections is true
disabled sections will defer to correspond sections to see if they use cloth (non-cloth sections
are disabled and another section added when cloth is enabled, using this flag allows for a check
on the original section to succeed)

Target is Skeletal Mesh

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | In Section Index | Index to check |
| boolean | Check Corresponding Sections | Whether to check corresponding sections for disabled sections |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value |  |
