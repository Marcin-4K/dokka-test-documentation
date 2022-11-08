---
title: Incrementor
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.math.utils](../index.html)/[Incrementor](index.html)



# Incrementor



[common]\
class [Incrementor](index.html)(start: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), cb: [Incrementor.MaxCountExceededCallback](-max-count-exceeded-callback/index.html)) : [Iterator](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterator/index.html)&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt;



## Constructors


| | |
|---|---|
| [Incrementor](-incrementor.html) | [common]<br>fun [Incrementor](-incrementor.html)(start: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), step: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), cb: [Incrementor.MaxCountExceededCallback](-max-count-exceeded-callback/index.html)) |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [common]<br>object [Companion](-companion/index.html) |
| [MaxCountExceededCallback](-max-count-exceeded-callback/index.html) | [common]<br>interface [MaxCountExceededCallback](-max-count-exceeded-callback/index.html) |


## Functions


| Name | Summary |
|---|---|
| [hasNext](has-next.html) | [common]<br>open operator override fun [hasNext](has-next.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [increment](increment.html) | [common]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)<br>fun [increment](increment.html)(nTimes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1) |
| [next](next.html) | [common]<br>open operator override fun [next](next.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [withCallback](with-callback.html) | [common]<br>fun [withCallback](with-callback.html)(cb: [Incrementor.MaxCountExceededCallback](-max-count-exceeded-callback/index.html)): [Incrementor](index.html) |
| [withMaximalCount](with-maximal-count.html) | [common]<br>fun [withMaximalCount](with-maximal-count.html)(max: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Incrementor](index.html) |


## Properties


| Name | Summary |
|---|---|
| [count](count.html) | [common]<br>var [count](count.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |

