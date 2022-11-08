---
title: Duration
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.units](../index.html)/[Duration](index.html)



# Duration



[common]\
data class [Duration](index.html) : [Freezable](../../net.graphmasters.multiplatform.core/-freezable/index.html), [Serializable](../../net.graphmasters.multiplatform.core/-serializable/index.html), [Comparable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-comparable/index.html)&lt;[Duration](index.html)&gt;



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [common]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [compareTo](compare-to.html) | [common]<br>open operator override fun [compareTo](compare-to.html)(other: [Duration](index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [equals](equals.html) | [common]<br>open operator override fun [equals](equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [freezeObject](../../net.graphmasters.multiplatform.core/-freezable/freeze-object.html) | [common]<br>expect fun [freezeObject](../../net.graphmasters.multiplatform.core/-freezable/freeze-object.html)() |
| [hashCode](hash-code.html) | [common]<br>open override fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [hours](hours.html) | [common]<br>fun [hours](hours.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [milliseconds](milliseconds.html) | [common]<br>fun [milliseconds](milliseconds.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [minus](minus.html) | [common]<br>operator fun [minus](minus.html)(other: [Duration](index.html)): [Duration](index.html) |
| [minutes](minutes.html) | [common]<br>fun [minutes](minutes.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [plus](plus.html) | [common]<br>operator fun [plus](plus.html)(other: [Duration](index.html)): [Duration](index.html) |
| [seconds](seconds.html) | [common]<br>fun [seconds](seconds.html)(): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |


## Extensions


| Name | Summary |
|---|---|
| [from](../from.html) | [ios]<br>fun [Duration](index.html#294327114%2FExtensions%2F-708110912).[from](../from.html)(timeInterval: NSTimeInterval): [Duration](index.html#294327114%2FExtensions%2F-708110912) |
| [timeInterval](../time-interval.html) | [ios]<br>val [Duration](index.html#294327114%2FExtensions%2F-708110912).[timeInterval](../time-interval.html): NSTimeInterval |

