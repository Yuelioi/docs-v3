---
title: pcfilter
order: 10
---
`<type> pcfilter(int handle, string channel_name, ...)`

Filters the points queued up by [pcopen](pcopen.html "Returns a handle to a point cloud file.")
using a simple reconstruction filter.

This function is roughly equivalent to:

```vex
float pcfilter(int handle; string channel)
{
    float    sum, w, d;
    float    value, result = 0;
    while (pciterate(handle))
    {
        pcimport(handle, "point.distance", d);
        pcimport(handle, channel, value);
        w = 1 - smooth(0, radius, d);
        sum += w;
        result += w * value;
    }
    result /= sum;
    return result;
}

```

`pcfilter` takes the points that were opened by the point cloud and produces a filtered value. The following equation shows how the individual points are weighted.

```vex
w_i = 1-smooth(0, maxd*1.1, d_i);

```

`maxd` is the farthest point, and `w_i` is the weight for a given point at distance (`d_i`). Points that are closer to the center will be weighted higher with that formula, rather than it being an average.
