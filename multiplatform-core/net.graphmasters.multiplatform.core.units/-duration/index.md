//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.units](../index.md)/[Duration](index.md)

# Duration

[common]\
data class [Duration](index.md) : [Freezable](../../net.graphmasters.multiplatform.core/-freezable/index.md), [Serializable](../../net.graphmasters.multiplatform.core/-serializable/index.md), [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)&lt;[Duration](index.md)&gt;

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [common]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [compareTo](compare-to.md) | [common]<br>open operator override fun [compareTo](compare-to.md)(other: [Duration](index.md)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [equals](equals.md) | [common]<br>open operator override fun [equals](equals.md)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [freezeObject](../../net.graphmasters.multiplatform.core/-freezable/freeze-object.md) | [common]<br>expect fun [freezeObject](../../net.graphmasters.multiplatform.core/-freezable/freeze-object.md)() |
| [hashCode](hash-code.md) | [common]<br>open override fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [hours](hours.md) | [common]<br>fun [hours](hours.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [milliseconds](milliseconds.md) | [common]<br>fun [milliseconds](milliseconds.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [minus](minus.md) | [common]<br>operator fun [minus](minus.md)(other: [Duration](index.md)): [Duration](index.md) |
| [minutes](minutes.md) | [common]<br>fun [minutes](minutes.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [plus](plus.md) | [common]<br>operator fun [plus](plus.md)(other: [Duration](index.md)): [Duration](index.md) |
| [seconds](seconds.md) | [common]<br>fun [seconds](seconds.md)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |

## Extensions

| Name | Summary |
|---|---|
| [from](../from.md) | [ios]<br>fun [Duration](index.md#294327114%2FExtensions%2F-183831061).[from](../from.md)(timeInterval: NSTimeInterval): [Duration](index.md#294327114%2FExtensions%2F-183831061) |
| [timeInterval](../time-interval.md) | [ios]<br>val [Duration](index.md#294327114%2FExtensions%2F-183831061).[timeInterval](../time-interval.md): NSTimeInterval |
