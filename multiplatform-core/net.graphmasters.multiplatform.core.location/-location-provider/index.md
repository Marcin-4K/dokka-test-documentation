---
title: LocationProvider
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.location](../index.html)/[LocationProvider](index.html)



# LocationProvider



[common]\
interface [LocationProvider](index.html)



## Types


| Name | Summary |
|---|---|
| [LocationUpdateListener](-location-update-listener/index.html) | [common]<br>interface [LocationUpdateListener](-location-update-listener/index.html) |


## Functions


| Name | Summary |
|---|---|
| [addLocationUpdateListener](add-location-update-listener.html) | [common]<br>abstract fun [addLocationUpdateListener](add-location-update-listener.html)(locationUpdateListener: [LocationProvider.LocationUpdateListener](-location-update-listener/index.html)) |
| [removeLocationUpdateListener](remove-location-update-listener.html) | [common]<br>abstract fun [removeLocationUpdateListener](remove-location-update-listener.html)(locationUpdateListener: [LocationProvider.LocationUpdateListener](-location-update-listener/index.html)) |
| [startLocationUpdates](start-location-updates.html) | [common]<br>abstract fun [startLocationUpdates](start-location-updates.html)() |
| [stopLocationUpdates](stop-location-updates.html) | [common]<br>abstract fun [stopLocationUpdates](stop-location-updates.html)() |


## Properties


| Name | Summary |
|---|---|
| [active](active.html) | [common]<br>abstract val [active](active.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [lastKnownLocation](last-known-location.html) | [common]<br>abstract val [lastKnownLocation](last-known-location.html): [Location](../-location/index.html)? |


## Inheritors


| Name |
|---|
| [FusedGpsLocationProvider](../-fused-gps-location-provider/index.html) |

