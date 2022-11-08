//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.geodesy](../index.md)/[Geodesy](index.md)/[distanceFromPointOntoSegment](distance-from-point-onto-segment.md)

# distanceFromPointOntoSegment

[common]\
fun [distanceFromPointOntoSegment](distance-from-point-onto-segment.md)(base: [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.md), start: [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.md), end: [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.md)): [Length](../../net.graphmasters.multiplatform.core.units/-length/index.md)

Projects a point onto a straight segment (defined by two points). The project point is must be between (or on) the start and end of the segment.

#### Return

The projected point

## Parameters

common

| | |
|---|---|
| base | The point to be projected onto the segment |
| start | Start of the segment |
| end | end of the segment |
