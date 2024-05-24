---
display_name: isbound
order: 6
---
`int  isbound(string variable_name)`

Parameters in VEX can be overridden by geometry attributes (if the
attributes exist on the surface being rendered). If the geometry
overrides the default attribute, this function will return 1. Otherwise
it will return 0.

Note
Though this function is defined for all contexts, it is only useful in the Displacement, Surface, and SOP contexts. No other contexts

can currently bind geometry attributes to VEX variables.

Example, in a SOP function:

```vex
sop
mycolor(vector uv=0; string map="")
{
if (isbound("uv") && map != "")
{
    // User has texture coordinates here, so create
    // velocity based on a texture map.
    v = colormap(map, uv);
}
else
{
    // No texture coordinates, so use a random value
    v = random(id);
}

```

Note
`isbound` does not tell you if the attribute exists. It tells you if the attribute is bound. If you added an `@a` to a wrangle to bind the `a`, then `isbound` will work as you expect in CVEX. Without an `@a`, there is no parameter in your CVEX function to bind the attribute to, so it will be unbound.
