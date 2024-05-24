---
display_name: Get Current Light Estimate
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR Augmented Reality](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality) > [Light Estimate](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality/LightEstimate)

An AugmentedReality session can be configured to provide light estimates.
The specific approach to light estimation can be configured by the \\c UARSessionConfig
specified during \\c StartARSession(). This function assumes that you will cast
the returned \\c UARLightEstimate to a derived type corresponding to your
session config.

Target is ARBlueprint Library

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | a \\c UARLighEstimate that can be cast to a derived class. |
