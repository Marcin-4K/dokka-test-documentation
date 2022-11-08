//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.utils](../index.md)/[Incrementor](index.md)

# Incrementor

[common]\
class [Incrementor](index.md)(start: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), cb: [Incrementor.MaxCountExceededCallback](-max-count-exceeded-callback/index.md)) : [Iterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;

## Constructors

| | |
|---|---|
| [Incrementor](-incrementor.md) | [common]<br>fun [Incrementor](-incrementor.md)(start: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), cb: [Incrementor.MaxCountExceededCallback](-max-count-exceeded-callback/index.md)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [common]<br>object [Companion](-companion/index.md) |
| [MaxCountExceededCallback](-max-count-exceeded-callback/index.md) | [common]<br>interface [MaxCountExceededCallback](-max-count-exceeded-callback/index.md) |

## Functions

| Name | Summary |
|---|---|
| [hasNext](has-next.md) | [common]<br>open operator override fun [hasNext](has-next.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [increment](increment.md) | [common]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)<br>fun [increment](increment.md)(nTimes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1) |
| [next](next.md) | [common]<br>open operator override fun [next](next.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [withCallback](with-callback.md) | [common]<br>fun [withCallback](with-callback.md)(cb: [Incrementor.MaxCountExceededCallback](-max-count-exceeded-callback/index.md)): [Incrementor](index.md) |
| [withMaximalCount](with-maximal-count.md) | [common]<br>fun [withMaximalCount](with-maximal-count.md)(max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Incrementor](index.md) |

## Properties

| Name | Summary |
|---|---|
| [count](count.md) | [common]<br>var [count](count.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
