---
display_name: Run Hardware Benchmark
order: 102
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Settings](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Settings)

Runs the hardware benchmark and populates ScalabilityQuality as well as the last benchmark results config members, but does not apply the settings it determines. Designed to be called in conjunction with ApplyHardwareBenchmarkResults

Target is Game User Settings

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Work Scale |  |
| real | CPUMultiplier |  |
| real | GPUMultiplier |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
