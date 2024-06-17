---
title: Find Socket and Index
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation)

Find a socket object in this SkeletalMesh by name.
Entering NAME_None will return NULL. If there are multiple sockets with the same name, will return the first one.
Also returns the index for the socket allowing for future fast access via GetSocketByIndex()

Target is Skeletal Mesh

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | In Socket Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Out Index |  |
| object | Return Value | Find a socket object in this SkeletalMesh by name.Entering NAME_None will return NULL. If there are multiple sockets with the same name, will return the first one.Also returns the index for the socket allowing for future fast access via GetSocketByIndex() |
