//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.location](../index.md)/[FusedGpsLocationProvider](index.md)

# FusedGpsLocationProvider

[android]\
class [FusedGpsLocationProvider](index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), locationConverter: [LocationConverter](../-location-converter/index.md)) : LocationProvider, [LocationListener](https://developer.android.com/reference/kotlin/android/location/LocationListener.html)

## Constructors

| | |
|---|---|
| [FusedGpsLocationProvider](-fused-gps-location-provider.md) | [android]<br>fun [FusedGpsLocationProvider](-fused-gps-location-provider.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)) |
| [FusedGpsLocationProvider](-fused-gps-location-provider.md) | [android]<br>fun [FusedGpsLocationProvider](-fused-gps-location-provider.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), locationConverter: [LocationConverter](../-location-converter/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [addLocationUpdateListener](add-location-update-listener.md) | [android]<br>open override fun [addLocationUpdateListener](add-location-update-listener.md)(locationUpdateListener: LocationProvider.LocationUpdateListener) |
| [onLocationChanged](on-location-changed.md) | [android]<br>open override fun [onLocationChanged](on-location-changed.md)(location: [Location](https://developer.android.com/reference/kotlin/android/location/Location.html)) |
| [onProviderDisabled](on-provider-disabled.md) | [android]<br>open override fun [onProviderDisabled](on-provider-disabled.md)(provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [onProviderEnabled](on-provider-enabled.md) | [android]<br>open override fun [onProviderEnabled](on-provider-enabled.md)(provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [onStatusChanged](on-status-changed.md) | [android]<br>~~open~~ ~~override~~ ~~fun~~ [~~onStatusChanged~~](on-status-changed.md)~~(~~provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), extras: [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html)?~~)~~ |
| [removeLocationUpdateListener](remove-location-update-listener.md) | [android]<br>open override fun [removeLocationUpdateListener](remove-location-update-listener.md)(locationUpdateListener: LocationProvider.LocationUpdateListener) |
| [startLocationUpdates](start-location-updates.md) | [android]<br>@[Synchronized](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-synchronized/index.html)<br>open override fun [startLocationUpdates](start-location-updates.md)() |
| [stopLocationUpdates](stop-location-updates.md) | [android]<br>open override fun [stopLocationUpdates](stop-location-updates.md)() |

## Properties

| Name | Summary |
|---|---|
| [active](active.md) | [android]<br>open override var [active](active.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [lastKnownLocation](last-known-location.md) | [android]<br>open override var [lastKnownLocation](last-known-location.md): Location? = null |
