---
title: shiftByCartesian
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.geodesy](../index.html)/[Geodesy](index.html)/[shiftByCartesian](shift-by-cartesian.html)



# shiftByCartesian



[common]\
fun [shiftByCartesian](shift-by-cartesian.html)(position: [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.html), shift: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.html)



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
fun [shiftByCartesian](shift-by-cartesian.html)(position: [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.html), metersNorth: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), metersEast: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.html)



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




