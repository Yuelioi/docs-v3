---
display_name: Get ViewportStatsSubsystem
order: 75
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [World Subsystems](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WorldSubsystems)

Get Viewport Stats Subsystem (World Subsystem)

The Viewport Stats Subsystem offers the ability to add messages to the current
viewport such as "LIGHTING NEEDS TO BE REBUILT" and "BLUEPRINT COMPILE ERROR".

Example usage:

if (UViewportStatsSubsystem\* ViewportSubsystem = GetWorld()->GetSubsystem())
{
// Bind a member function delegate to the subsystem...
FViewportDisplayCallback Callback;
Callback.BindDynamic(this, &UCustomClass::DisplayViewportMessage);
ViewportSubsystem->AddDisplayDelegate(Callback);

// ... or use inline lambda functions
ViewportSubsystem->AddDisplayDelegate(
{
// Some kind of state management
OutText = NSLOCTEXT("FooNamespace", "Blarg", "Display message here");
OutColor = FLinearColor::Red;
return bShouldDisplay;
});
}

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |
