//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.geodesy](../index.md)/[Geodesy](index.md)/[shiftByPolarInDegrees](shift-by-polar-in-degrees.md)

# shiftByPolarInDegrees

[common]\
fun [shiftByPolarInDegrees](shift-by-polar-in-degrees.md)(position: [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.md), meters: [Length](../../net.graphmasters.multiplatform.core.units/-length/index.md), heading: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.md)

Shifts a Geo-Position by some meters in a certain heading (in degrees). Only works for short distances.

#### Return

The shifted Geo-Position

## Parameters

common

| | |
|---|---|
| position | The starting Geo-Position |
| meters | meters to be shifted |
| heading | angle in degrees (0 is north and 90 is east) |
