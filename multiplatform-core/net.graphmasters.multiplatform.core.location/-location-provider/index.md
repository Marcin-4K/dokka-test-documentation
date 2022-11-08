//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.location](../index.md)/[LocationProvider](index.md)

# LocationProvider

[common]\
interface [LocationProvider](index.md)

## Types

| Name | Summary |
|---|---|
| [LocationUpdateListener](-location-update-listener/index.md) | [common]<br>interface [LocationUpdateListener](-location-update-listener/index.md) |

## Functions

| Name | Summary |
|---|---|
| [addLocationUpdateListener](add-location-update-listener.md) | [common]<br>abstract fun [addLocationUpdateListener](add-location-update-listener.md)(locationUpdateListener: [LocationProvider.LocationUpdateListener](-location-update-listener/index.md)) |
| [removeLocationUpdateListener](remove-location-update-listener.md) | [common]<br>abstract fun [removeLocationUpdateListener](remove-location-update-listener.md)(locationUpdateListener: [LocationProvider.LocationUpdateListener](-location-update-listener/index.md)) |
| [startLocationUpdates](start-location-updates.md) | [common]<br>abstract fun [startLocationUpdates](start-location-updates.md)() |
| [stopLocationUpdates](stop-location-updates.md) | [common]<br>abstract fun [stopLocationUpdates](stop-location-updates.md)() |

## Properties

| Name | Summary |
|---|---|
| [active](active.md) | [common]<br>abstract val [active](active.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [lastKnownLocation](last-known-location.md) | [common]<br>abstract val [lastKnownLocation](last-known-location.md): [Location](../-location/index.md)? |

## Inheritors

| Name |
|---|
| [FusedGpsLocationProvider](../-fused-gps-location-provider/index.md) |
