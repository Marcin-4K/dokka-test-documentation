//[multiplatform-core](../../index.md)/[net.graphmasters.multiplatform.core.location](index.md)

# Package net.graphmasters.multiplatform.core.location

## Types

| Name | Summary |
|---|---|
| [AndroidLocationConverter](-android-location-converter/index.md) | [android]<br>class [AndroidLocationConverter](-android-location-converter/index.md)(timeProvider: TimeProvider) : [LocationConverter](-location-converter/index.md) |
| [FusedGpsLocationProvider](-fused-gps-location-provider/index.md) | [android]<br>class [FusedGpsLocationProvider](-fused-gps-location-provider/index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), locationConverter: [LocationConverter](-location-converter/index.md)) : LocationProvider, [LocationListener](https://developer.android.com/reference/kotlin/android/location/LocationListener.html) |
| [GpsUtils](-gps-utils/index.md) | [android]<br>object [GpsUtils](-gps-utils/index.md) |
| [Location](-location/index.md) | [common]<br>open class [Location](-location/index.md)(val provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;no provider&quot;, val timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0, val latLng: [LatLng](../net.graphmasters.multiplatform.core.model/-lat-lng/index.md), val altitude: [Length](../net.graphmasters.multiplatform.core.units/-length/index.md)? = null, val heading: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null, val speed: [Speed](../net.graphmasters.multiplatform.core.units/-speed/index.md)? = null, val accuracy: [Length](../net.graphmasters.multiplatform.core.units/-length/index.md)? = null, val level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null) : [Freezable](../net.graphmasters.multiplatform.core/-freezable/index.md) |
| [LocationConverter](-location-converter/index.md) | [android]<br>interface [LocationConverter](-location-converter/index.md) |
| [LocationProvider](-location-provider/index.md) | [common]<br>interface [LocationProvider](-location-provider/index.md) |

## Functions

| Name | Summary |
|---|---|
| [distanceFrom](distance-from.md) | [ios]<br>fun [Location](-location/index.md#-975294955%2FExtensions%2F-183831061).[distanceFrom](distance-from.md)(location: [Location](-location/index.md#-975294955%2FExtensions%2F-183831061)): Length |
| [from](from.md) | [ios]<br>fun [Location.Companion](-location/-companion/index.md#-98438057%2FExtensions%2F-183831061).[from](from.md)(latLng: [LatLng](../net.graphmasters.multiplatform.core.model/-lat-lng/index.md#94959378%2FExtensions%2F-183831061)): [Location](-location/index.md#-975294955%2FExtensions%2F-183831061)<br>fun [Location.Companion](-location/-companion/index.md#-98438057%2FExtensions%2F-183831061).[from](from.md)(clLocation: CLLocation): [Location](-location/index.md#-975294955%2FExtensions%2F-183831061) |

## Properties

| Name | Summary |
|---|---|
| [clLocation](cl-location.md) | [ios]<br>val [Location](-location/index.md#-975294955%2FExtensions%2F-183831061).[clLocation](cl-location.md): CLLocation |
