---
title: shiftByPolarInRadians
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.geodesy](../index.html)/[Geodesy](index.html)/[shiftByPolarInRadians](shift-by-polar-in-radians.html)



# shiftByPolarInRadians



[common]\
fun [shiftByPolarInRadians](shift-by-polar-in-radians.html)(position: [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.html), meters: [Length](../../net.graphmasters.multiplatform.core.units/-length/index.html), heading: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.html)



Shifts a Geo-Position by some meters in a certain heading (in degrees). Only works for short distances.



#### Return



The shifted Geo-Position



## Parameters


common

| | |
|---|---|
| position | The starting Geo-Position |
| meters | meters to be shifted |
| heading | angle in radians (0 is north and Pi/2 is east) |




