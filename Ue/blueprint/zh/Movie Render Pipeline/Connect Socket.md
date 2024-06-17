---
title: Connect Socket
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Attempts to connect a socket to the specified host and port. This is a blocking call.

Target is Movie Pipeline Executor Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | In Host Name | The host name as to connect to such as "127.0.0.1" |
| integer | In Port | The port to attempt to connect to the host on. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the socket was succesfully connected to the given host and port. |
