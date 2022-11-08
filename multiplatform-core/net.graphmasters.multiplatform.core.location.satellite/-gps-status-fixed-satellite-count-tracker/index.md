//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.location.satellite](../index.md)/[GpsStatusFixedSatelliteCountTracker](index.md)

# GpsStatusFixedSatelliteCountTracker

[android]\
class [GpsStatusFixedSatelliteCountTracker](index.md)(locationManager: [LocationManager](https://developer.android.com/reference/kotlin/android/location/LocationManager.html)) : [LocationListener](https://developer.android.com/reference/kotlin/android/location/LocationListener.html), [FixedSatelliteCountTracker](../-fixed-satellite-count-tracker/index.md)

## Constructors

| | |
|---|---|
| [GpsStatusFixedSatelliteCountTracker](-gps-status-fixed-satellite-count-tracker.md) | [android]<br>fun [GpsStatusFixedSatelliteCountTracker](-gps-status-fixed-satellite-count-tracker.md)(locationManager: [LocationManager](https://developer.android.com/reference/kotlin/android/location/LocationManager.html)) |

## Functions

| Name | Summary |
|---|---|
| [onLocationChanged](on-location-changed.md) | [android]<br>open override fun [onLocationChanged](on-location-changed.md)(location: [Location](https://developer.android.com/reference/kotlin/android/location/Location.html)) |
| [onProviderDisabled](on-provider-disabled.md) | [android]<br>open override fun [onProviderDisabled](on-provider-disabled.md)(provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [onProviderEnabled](on-provider-enabled.md) | [android]<br>open override fun [onProviderEnabled](on-provider-enabled.md)(provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [onStatusChanged](on-status-changed.md) | [android]<br>open override fun [onStatusChanged](on-status-changed.md)(provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), extras: [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html)?) |
| [start](start.md) | [android]<br>open override fun [start](start.md)(callback: ([Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [stop](stop.md) | [android]<br>open override fun [stop](stop.md)() |

## Properties

| Name | Summary |
|---|---|
| [satelliteCount](satellite-count.md) | [android]<br>open override var [satelliteCount](satellite-count.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
