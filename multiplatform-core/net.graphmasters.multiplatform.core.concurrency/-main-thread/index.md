//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.concurrency](../index.md)/[MainThread](index.md)

# MainThread

[common]\
expect object [MainThread](index.md)

[android, ios, jvm]\
actual object [MainThread](index.md)

## Functions

| Name | Summary |
|---|---|
| [execute](execute.md) | [common, android, ios, jvm]<br>[common]<br>expect fun [execute](execute.md)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html))<br>[android, ios, jvm]<br>actual fun [execute](execute.md)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [isCurrentThread](is-current-thread.md) | [common, android, ios, jvm]<br>[common]<br>expect fun [isCurrentThread](is-current-thread.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>[android, ios, jvm]<br>actual fun [isCurrentThread](is-current-thread.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
