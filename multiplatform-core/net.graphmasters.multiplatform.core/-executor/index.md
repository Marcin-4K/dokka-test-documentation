//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core](../index.md)/[Executor](index.md)

# Executor

[common]\
interface [Executor](index.md)

## Types

| Name | Summary |
|---|---|
| [Future](-future/index.md) | [common]<br>interface [Future](-future/index.md) |

## Functions

| Name | Summary |
|---|---|
| [execute](execute.md) | [common]<br>abstract fun [execute](execute.md)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [executeDelayed](execute-delayed.md) | [common]<br>abstract fun [executeDelayed](execute-delayed.md)(delay: [Duration](../../net.graphmasters.multiplatform.core.units/-duration/index.md), block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [Executor.Future](-future/index.md) |
| [runOnUiThread](run-on-ui-thread.md) | [common]<br>~~abstract~~ ~~fun~~ [~~runOnUiThread~~](run-on-ui-thread.md)~~(~~block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)~~)~~ |
| [schedule](schedule.md) | [common]<br>abstract fun [schedule](schedule.md)(updateRate: [Duration](../../net.graphmasters.multiplatform.core.units/-duration/index.md), block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [Executor.Future](-future/index.md) |

## Inheritors

| Name |
|---|
| [AndroidExecutor](../-android-executor/index.md) |
| [OperationQueueExecutor](../-operation-queue-executor/index.md) |
| [JVMExecutor](../-j-v-m-executor/index.md) |
