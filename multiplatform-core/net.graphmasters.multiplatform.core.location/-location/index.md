---
title: Location
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.location](../index.html)/[Location](index.html)



# Location



[common]\
open class [Location](index.html)(val provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;no provider&quot;, val timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0, val latLng: [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.html), val altitude: [Length](../../net.graphmasters.multiplatform.core.units/-length/index.html)? = null, val heading: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null, val speed: [Speed](../../net.graphmasters.multiplatform.core.units/-speed/index.html)? = null, val accuracy: [Length](../../net.graphmasters.multiplatform.core.units/-length/index.html)? = null, val level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null) : [Freezable](../../net.graphmasters.multiplatform.core/-freezable/index.html)



## Constructors


| | |
|---|---|
| [Location](-location.html) | [common]<br>fun [Location](-location.html)(location: [Location](index.html)) |
| [Location](-location.html) | [common]<br>fun [Location](-location.html)(provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;no provider&quot;, timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0, latLng: [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.html), altitude: [Length](../../net.graphmasters.multiplatform.core.units/-length/index.html)? = null, heading: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null, speed: [Speed](../../net.graphmasters.multiplatform.core.units/-speed/index.html)? = null, accuracy: [Length](../../net.graphmasters.multiplatform.core.units/-length/index.html)? = null, level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null) |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [common]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [equals](equals.html) | [common]<br>open operator override fun [equals](equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [freezeObject](../../net.graphmasters.multiplatform.core/-freezable/freeze-object.html) | [common]<br>expect fun [freezeObject](../../net.graphmasters.multiplatform.core/-freezable/freeze-object.html)() |
| [hashCode](hash-code.html) | [common]<br>open override fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |


## Properties


| Name | Summary |
|---|---|
| [accuracy](accuracy.html) | [common]<br>val [accuracy](accuracy.html): [Length](../../net.graphmasters.multiplatform.core.units/-length/index.html)? = null |
| [altitude](altitude.html) | [common]<br>val [altitude](altitude.html): [Length](../../net.graphmasters.multiplatform.core.units/-length/index.html)? = null |
| [heading](heading.html) | [common]<br>val [heading](heading.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null |
| [latLng](lat-lng.html) | [common]<br>val [latLng](lat-lng.html): [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.html) |
| [level](level.html) | [common]<br>val [level](level.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [provider](provider.html) | [common]<br>val [provider](provider.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [speed](speed.html) | [common]<br>val [speed](speed.html): [Speed](../../net.graphmasters.multiplatform.core.units/-speed/index.html)? = null |
| [timestamp](timestamp.html) | [common]<br>val [timestamp](timestamp.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0 |


## Extensions


| Name | Summary |
|---|---|
| [clLocation](../cl-location.html) | [ios]<br>val [Location](index.html#-975294955%2FExtensions%2F-708110912).[clLocation](../cl-location.html): CLLocation |
| [distanceFrom](../distance-from.html) | [ios]<br>fun [Location](index.html#-975294955%2FExtensions%2F-708110912).[distanceFrom](../distance-from.html)(location: [Location](index.html#-975294955%2FExtensions%2F-708110912)): Length |

