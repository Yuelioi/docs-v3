---
display_name: Get CPUCore Utilization
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Meta Sound Perf](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MetaSoundPerf)

Get the CPU usage as "fraction of real time" used to render this metasound.
NOTE: The MetasoundSource asset MUST have had its EnableRenderTiming function called
before the metasound is started!

Target is Metasound Generator Handle

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Get the CPU usage as "fraction of real time" used to render this metasound.NOTE: The MetasoundSource asset MUST have had its EnableRenderTiming function calledbefore the metasound is started! |
