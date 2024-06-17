---
title: Enable Runtime Render Timing
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Meta Sound Perf](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MetaSoundPerf)

Enable the profiling of the MetaSound render for this playing instance. You
must call this before calling "GetRuntimeCPUCoreUtilization" (below) or you will just
get 0.0 back for core utilization.

Target is Metasound Generator Handle

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Enable |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
