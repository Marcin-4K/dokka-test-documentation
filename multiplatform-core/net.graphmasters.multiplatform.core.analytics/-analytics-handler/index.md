---
title: AnalyticsHandler
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.analytics](../index.html)/[AnalyticsHandler](index.html)



# AnalyticsHandler



[common]\
interface [AnalyticsHandler](index.html)



## Types


| Name | Summary |
|---|---|
| [Type](-type/index.html) | [common]<br>enum [Type](-type/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[AnalyticsHandler.Type](-type/index.html)&gt; |


## Functions


| Name | Summary |
|---|---|
| [postError](post-error.html) | [common]<br>abstract fun [postError](post-error.html)(throwable: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), properties: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt;) |
| [postEvent](post-event.html) | [common]<br>abstract fun [postEvent](post-event.html)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), properties: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt;, type: [AnalyticsHandler.Type](-type/index.html)) |

