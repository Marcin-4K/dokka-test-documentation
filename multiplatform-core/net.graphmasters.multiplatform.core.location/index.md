---
title: net.graphmasters.multiplatform.core.location
---
//[multiplatform-core](../../index.html)/[net.graphmasters.multiplatform.core.location](index.html)



# Package net.graphmasters.multiplatform.core.location



## Types


| Name | Summary |
|---|---|
| [AndroidLocationConverter](-android-location-converter/index.html) | [android]<br>class [AndroidLocationConverter](-android-location-converter/index.html)(timeProvider: TimeProvider) : [LocationConverter](-location-converter/index.html) |
| [FusedGpsLocationProvider](-fused-gps-location-provider/index.html) | [android]<br>class [FusedGpsLocationProvider](-fused-gps-location-provider/index.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), locationConverter: [LocationConverter](-location-converter/index.html)) : LocationProvider, [LocationListener](https://developer.android.com/reference/kotlin/android/location/LocationListener.html) |
| [GpsUtils](-gps-utils/index.html) | [android]<br>object [GpsUtils](-gps-utils/index.html) |
| [Location](-location/index.html) | [common]<br>open class [Location](-location/index.html)(val provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;no provider&quot;, val timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0, val latLng: [LatLng](../net.graphmasters.multiplatform.core.model/-lat-lng/index.html), val altitude: [Length](../net.graphmasters.multiplatform.core.units/-length/index.html)? = null, val heading: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null, val speed: [Speed](../net.graphmasters.multiplatform.core.units/-speed/index.html)? = null, val accuracy: [Length](../net.graphmasters.multiplatform.core.units/-length/index.html)? = null, val level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null) : [Freezable](../net.graphmasters.multiplatform.core/-freezable/index.html) |
| [LocationConverter](-location-converter/index.html) | [android]<br>interface [LocationConverter](-location-converter/index.html) |
| [LocationProvider](-location-provider/index.html) | [common]<br>interface [LocationProvider](-location-provider/index.html) |


## Functions


| Name | Summary |
|---|---|
| [distanceFrom](distance-from.html) | [ios]<br>fun [Location](-location/index.html#-975294955%2FExtensions%2F-708110912).[distanceFrom](distance-from.html)(location: [Location](-location/index.html#-975294955%2FExtensions%2F-708110912)): Length |
| [from](from.html) | [ios]<br>fun [Location.Companion](-location/-companion/index.html#-98438057%2FExtensions%2F-708110912).[from](from.html)(latLng: [LatLng](../net.graphmasters.multiplatform.core.model/-lat-lng/index.html#94959378%2FExtensions%2F-708110912)): [Location](-location/index.html#-975294955%2FExtensions%2F-708110912)<br>fun [Location.Companion](-location/-companion/index.html#-98438057%2FExtensions%2F-708110912).[from](from.html)(clLocation: CLLocation): [Location](-location/index.html#-975294955%2FExtensions%2F-708110912) |


## Properties


| Name | Summary |
|---|---|
| [clLocation](cl-location.html) | [ios]<br>val [Location](-location/index.html#-975294955%2FExtensions%2F-708110912).[clLocation](cl-location.html): CLLocation |

