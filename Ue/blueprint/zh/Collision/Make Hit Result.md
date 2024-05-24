---
display_name: Make Hit Result
order: 45
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Create a HitResult struct

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Blocking Hit | True if there was a blocking hit, false otherwise. |
| boolean | Initial Overlap | True if the hit started in an initial overlap. In this case some other values should be interpreted differently. Time will be 0, ImpactPoint will equal Location, and normals will be equal and indicate a depenetration vector. |
| real | Time | 'Time' of impact along trace direction ranging from \[0.0 to 1.0) if there is a hit, indicating time between start and end. Equals 1.0 if there is no hit. |
| real | Distance | The distance from the TraceStart to the Location in world space. This value is 0 if there was an initial overlap (trace started inside another colliding object). |
| vector | Location | Location of the hit in world space. If this was a swept shape test, this is the location where we can place the shape in the world where it will not penetrate. |
| vector | Impact Point | Location of the actual contact point of the trace shape with the surface of the hit object. Equal to Location in the case of an initial overlap. |
| vector | Normal | Normal of the hit in world space, for the object that was swept (e.g. for a sphere trace this points towards the sphere's center). Equal to ImpactNormal for line tests. |
| vector | Impact Normal | Normal of the hit in world space, for the object that was hit by the sweep. |
| object | Phys Mat | Physical material that was hit. Must set bReturnPhysicalMaterial to true in the query params for this to be returned. |
| object | Hit Actor | Actor hit by the trace. |
| object | Hit Component | PrimitiveComponent hit by the trace. |
| name | Hit Bone Name | Name of the bone hit (valid only if we hit a skeletal mesh). |
| name | Bone Name | Name of the trace bone hit (valid only if we hit a skeletal mesh). |
| integer | Hit Item | Primitive-specific data recording which item in the primitive was hit |
| integer | Element Index | If colliding with a primitive with multiple parts, index of the part that was hit. |
| integer | Face Index | If colliding with trimesh or landscape, index of face that was hit. |
| vector | Trace Start |  |
| vector | Trace End |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value |  |
