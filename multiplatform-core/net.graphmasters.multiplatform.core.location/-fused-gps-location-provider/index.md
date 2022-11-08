---
title: FusedGpsLocationProvider
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.location](../index.html)/[FusedGpsLocationProvider](index.html)



# FusedGpsLocationProvider



[android]\
class [FusedGpsLocationProvider](index.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), locationConverter: [LocationConverter](../-location-converter/index.html)) : LocationProvider, [LocationListener](https://developer.android.com/reference/kotlin/android/location/LocationListener.html)



## Constructors


| | |
|---|---|
| [FusedGpsLocationProvider](-fused-gps-location-provider.html) | [android]<br>fun [FusedGpsLocationProvider](-fused-gps-location-provider.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)) |
| [FusedGpsLocationProvider](-fused-gps-location-provider.html) | [android]<br>fun [FusedGpsLocationProvider](-fused-gps-location-provider.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), locationConverter: [LocationConverter](../-location-converter/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [addLocationUpdateListener](add-location-update-listener.html) | [android]<br>open override fun [addLocationUpdateListener](add-location-update-listener.html)(locationUpdateListener: LocationProvider.LocationUpdateListener) |
| [onLocationChanged](on-location-changed.html) | [android]<br>open override fun [onLocationChanged](on-location-changed.html)(location: [Location](https://developer.android.com/reference/kotlin/android/location/Location.html)) |
| [onProviderDisabled](on-provider-disabled.html) | [android]<br>open override fun [onProviderDisabled](on-provider-disabled.html)(provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [onProviderEnabled](on-provider-enabled.html) | [android]<br>open override fun [onProviderEnabled](on-provider-enabled.html)(provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [onStatusChanged](on-status-changed.html) | [android]<br>~~open~~ ~~override~~ ~~fun~~ [~~onStatusChanged~~](on-status-changed.html)~~(~~provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), extras: [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html)?~~)~~ |
| [removeLocationUpdateListener](remove-location-update-listener.html) | [android]<br>open override fun [removeLocationUpdateListener](remove-location-update-listener.html)(locationUpdateListener: LocationProvider.LocationUpdateListener) |
| [startLocationUpdates](start-location-updates.html) | [android]<br>@[Synchronized](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-synchronized/index.html)<br>open override fun [startLocationUpdates](start-location-updates.html)() |
| [stopLocationUpdates](stop-location-updates.html) | [android]<br>open override fun [stopLocationUpdates](stop-location-updates.html)() |


## Properties


| Name | Summary |
|---|---|
| [active](active.html) | [android]<br>open override var [active](active.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [lastKnownLocation](last-known-location.html) | [android]<br>open override var [lastKnownLocation](last-known-location.html): Location? = null |

