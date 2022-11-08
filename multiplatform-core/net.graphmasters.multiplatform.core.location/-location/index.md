//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.location](../index.md)/[Location](index.md)

# Location

[common]\
open class [Location](index.md)(val provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;no provider&quot;, val timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0, val latLng: [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.md), val altitude: [Length](../../net.graphmasters.multiplatform.core.units/-length/index.md)? = null, val heading: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null, val speed: [Speed](../../net.graphmasters.multiplatform.core.units/-speed/index.md)? = null, val accuracy: [Length](../../net.graphmasters.multiplatform.core.units/-length/index.md)? = null, val level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null) : [Freezable](../../net.graphmasters.multiplatform.core/-freezable/index.md)

## Constructors

| | |
|---|---|
| [Location](-location.md) | [common]<br>fun [Location](-location.md)(location: [Location](index.md)) |
| [Location](-location.md) | [common]<br>fun [Location](-location.md)(provider: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;no provider&quot;, timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0, latLng: [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.md), altitude: [Length](../../net.graphmasters.multiplatform.core.units/-length/index.md)? = null, heading: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null, speed: [Speed](../../net.graphmasters.multiplatform.core.units/-speed/index.md)? = null, accuracy: [Length](../../net.graphmasters.multiplatform.core.units/-length/index.md)? = null, level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [common]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | [common]<br>open operator override fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [freezeObject](../../net.graphmasters.multiplatform.core/-freezable/freeze-object.md) | [common]<br>expect fun [freezeObject](../../net.graphmasters.multiplatform.core/-freezable/freeze-object.md)() |
| [hashCode](hash-code.md) | [common]<br>open override fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

## Properties

| Name | Summary |
|---|---|
| [accuracy](accuracy.md) | [common]<br>val [accuracy](accuracy.md): [Length](../../net.graphmasters.multiplatform.core.units/-length/index.md)? = null |
| [altitude](altitude.md) | [common]<br>val [altitude](altitude.md): [Length](../../net.graphmasters.multiplatform.core.units/-length/index.md)? = null |
| [heading](heading.md) | [common]<br>val [heading](heading.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)? = null |
| [latLng](lat-lng.md) | [common]<br>val [latLng](lat-lng.md): [LatLng](../../net.graphmasters.multiplatform.core.model/-lat-lng/index.md) |
| [level](level.md) | [common]<br>val [level](level.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [provider](provider.md) | [common]<br>val [provider](provider.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [speed](speed.md) | [common]<br>val [speed](speed.md): [Speed](../../net.graphmasters.multiplatform.core.units/-speed/index.md)? = null |
| [timestamp](timestamp.md) | [common]<br>val [timestamp](timestamp.md): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0 |

## Extensions

| Name | Summary |
|---|---|
| [clLocation](../cl-location.md) | [ios]<br>val [Location](index.md#-975294955%2FExtensions%2F-183831061).[clLocation](../cl-location.md): CLLocation |
| [distanceFrom](../distance-from.md) | [ios]<br>fun [Location](index.md#-975294955%2FExtensions%2F-183831061).[distanceFrom](../distance-from.md)(location: [Location](index.md#-975294955%2FExtensions%2F-183831061)): Length |
