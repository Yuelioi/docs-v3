---
display_name: pcsampleleaf
order: 28
---
`void  pcsampleleaf(int handle, float sample)`

This function can only be used with the pcopenlod() function, and then only
within a pciterate() loop. It replaces the current iteration point with an
importance sampled leaf descendant of that point. The weighting used to
select the leaf point is the “area” channel provided to the pcopenlod()
function’s “measure” parameter, or a uniform weight if no area channel
was specified when opening the point cloud. The sample parameter is
expected to be a uniform random value between 0 and 1.

If the current iteration point is already a leaf point or the point cloud
was not opened with pcopenlod(), pcsampleleaf() has no effect.

This function is useful when aggregate point information cannot be used in
a meaningful way, and provides a mechanism to access the information
contained in child nodes in the point tree. For example, it wouldn’t make
sense to trace shadow rays from an averaged point position, but it is
useful to choose one of the child points and then send the shadow ray to
that point.
Example: Shadow Rays

## example-shadow-rays

```vex
// Open a point cloud and retrieve a single aggregate point representing the
// entire cloud
string texturename = "points.pc";
int handle = pcopenlod(texturename, "P", P, 8,
"measure", "solidangle",
"area", "A",
"samples", 1,
"aggregate:A", "sum",
"aggregate:P", "mean");

Cf = 0;

// This loop will iterate only once
while (pciterate(handle))
{
    // Query A from the averaged point
    float        ptarea;
    pcimport(handle, "A", ptarea);

    pcsampleleaf(handle, nrandom());

    // Query P from a sampled leaf point
    vector        pos;
    pcimport(handle, "P", pos);

    if (trace(pos, P-pos, Time))
        Cf += ptarea / length2(P-pos);
}

```
