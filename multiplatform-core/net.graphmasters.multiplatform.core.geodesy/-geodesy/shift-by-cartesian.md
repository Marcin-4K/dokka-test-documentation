//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.geodesy](../index.md)/[Geodesy](index.md)/[shiftByCartesian](shift-by-cartesian.md)

# shiftByCartesian

[common]\
fun [shiftByCartesian](shift-by-cartesian.md)(position: [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.md), shift: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.md)

Shifts a Geo-Position by some meters north and east. Only works for short distances.

#### Return

The shifted Geo-Position

## Parameters

common

| | |
|---|---|
| position | The starting Geo-Position |
| shift | Array of meters north and east to be shifted (in that order). |

[common]\
fun [shiftByCartesian](shift-by-cartesian.md)(position: [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.md), metersNorth: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), metersEast: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.md)

Shifts a Geo-Position by some meters north and east. Only works for short distances.

#### Return

The shifted Geo-Position

## Parameters

common

| | |
|---|---|
| position | The starting Geo-Position |
| metersNorth | meters north to be shifted |
| metersEast | meter east to be shifted |
