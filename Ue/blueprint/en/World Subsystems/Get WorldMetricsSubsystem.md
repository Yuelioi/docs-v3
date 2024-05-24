---
display_name: Get WorldMetricsSubsystem
order: 77
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [World Subsystems](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WorldSubsystems)

Get World Metrics Subsystem (World Subsystem)

World metrics subsystem

This subsystem provides an interface to add and remove world metrics implementing the UWorldMetricInterface class.

- Added metrics get automatically updated by the subsystem's ticker.
- The subsystem becomes an owner of all added metrics. The user is responsible for removing them when no longer
  needed so they can be garbage collected.
- Metrics can have extensions to add shared functionality.
- Extensions implement the UWorldMetricsExtension class and use Acquire/Release semantics. They can be acquired by
  either metrics or extensions. Initialization and deinitialization are the ideal phases to do so.
- The subsystem solely owns extensions and can automatically remove them for garbage collection whenever they are no
  longer acquired by any metric or extension.

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |
