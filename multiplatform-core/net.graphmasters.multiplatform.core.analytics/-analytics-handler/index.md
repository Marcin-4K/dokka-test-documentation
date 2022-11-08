//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.analytics](../index.md)/[AnalyticsHandler](index.md)

# AnalyticsHandler

[common]\
interface [AnalyticsHandler](index.md)

## Types

| Name | Summary |
|---|---|
| [Type](-type/index.md) | [common]<br>enum [Type](-type/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[AnalyticsHandler.Type](-type/index.md)&gt; |

## Functions

| Name | Summary |
|---|---|
| [postError](post-error.md) | [common]<br>abstract fun [postError](post-error.md)(throwable: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html), properties: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt;) |
| [postEvent](post-event.md) | [common]<br>abstract fun [postEvent](post-event.md)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), properties: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt;, type: [AnalyticsHandler.Type](-type/index.md)) |
