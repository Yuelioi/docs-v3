---
title: Apply Radial Impulse
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsObject)

Apply a physics radial impulse with an optional strain on a specific component
Effect is applied within a sphere. When using linear falloff the effect will be minimum at the outer edge of the sphere and maximum at its center

Target is Physics Object Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Component | Primitive component to apply the impulse / strain on |
| vector | Origin | Positition of the origin of the radial effect in world space |
| real | Radius | Radius of the radial effect ( beyond the radius, impulse will not be applied ) |
| real | Strength | Strength of the impulse to apply ( Unit : (Kg * m / s) or ( m /s ) if bVelChange is true |
| enum | Falloff | Type of falloff to use ( constant, linear ) |
| boolean | Apply Strain | Whether or not to apply strain on top of the impulse ( for destructible objects ) |
| real | Strain | If bApplyStrain is true, Strain to apply to the physics particles ( for destructible objects ) |
| boolean | Vel Change | If true, impulse Strength parameter is interpretation as a change of velocity |
| real | Min Value | When using linear falloff, this define the falloff value at the outer edge of the sphere |
| real | Max Value | When using linear falloff, this define the falloff value at the center of the sphere |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
