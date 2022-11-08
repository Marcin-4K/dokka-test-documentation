---
title: GpsStatusFixedSatelliteCountTracker
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.location.satellite](../index.html)/[GpsStatusFixedSatelliteCountTracker](index.html)



# GpsStatusFixedSatelliteCountTracker



[android]\
class [GpsStatusFixedSatelliteCountTracker](index.html)(locationManager: [LocationManager](https://developer.android.com/reference/kotlin/android/location/LocationManager.html)) : [LocationListener](https://developer.android.com/reference/kotlin/android/location/LocationListener.html), [FixedSatelliteCountTracker](../-fixed-satellite-count-tracker/index.html)



## Constructors


| | |
|---|---|
| [GpsStatusFixedSatelliteCountTracker](-gps-status-fixed-satellite-count-tracker.html) | [android]<br>fun [GpsStatusFixedSatelliteCountTracker](-gps-status-fixed-satellite-count-tracker.html)(locationManager: [LocationManager](https://developer.android.com/reference/kotlin/android/location/LocationManager.html)) |


## Functions


| Name | Summary |
|---|---|
| [onLocationChanged](on-location-changed.html) | [android]<br>open override fun [onLocationChanged](on-location-changed.html)(location: [Location](https://developer.android.com/reference/kotlin/android/location/Location.html)) |
| [onProviderDisabled](on-provider-disabled.html) | [android]<br>open override fun [onProviderDisabled](on-provider-disabled.html)(provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [onProviderEnabled](on-provider-enabled.html) | [android]<br>open override fun [onProviderEnabled](on-provider-enabled.html)(provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [onStatusChanged](on-status-changed.html) | [android]<br>open override fun [onStatusChanged](on-status-changed.html)(provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), extras: [Bundle](https://developer.android.com/reference/kotlin/android/os/Bundle.html)?) |
| [start](start.html) | [android]<br>open override fun [start](start.html)(callback: ([Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [stop](stop.html) | [android]<br>open override fun [stop](stop.html)() |


## Properties


| Name | Summary |
|---|---|
| [satelliteCount](satellite-count.html) | [android]<br>open override var [satelliteCount](satellite-count.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |

