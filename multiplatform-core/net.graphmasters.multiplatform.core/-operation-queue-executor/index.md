//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core](../index.md)/[OperationQueueExecutor](index.md)

# OperationQueueExecutor

[ios]\
class [OperationQueueExecutor](index.md) : Executor

## Constructors

| | |
|---|---|
| [OperationQueueExecutor](-operation-queue-executor.md) | [ios]<br>fun [OperationQueueExecutor](-operation-queue-executor.md)() |

## Functions

| Name | Summary |
|---|---|
| [execute](execute.md) | [ios]<br>open override fun [execute](execute.md)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [executeDelayed](execute-delayed.md) | [ios]<br>open override fun [executeDelayed](execute-delayed.md)(delay: [Duration](../../net.graphmasters.multiplatform.core.units/-duration/index.md#294327114%2FExtensions%2F-183831061), block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Executor.Future |
| [runOnUiThread](run-on-ui-thread.md) | [ios]<br>open override fun [runOnUiThread](run-on-ui-thread.md)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [schedule](schedule.md) | [ios]<br>open override fun [schedule](schedule.md)(updateRate: [Duration](../../net.graphmasters.multiplatform.core.units/-duration/index.md#294327114%2FExtensions%2F-183831061), block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Executor.Future |
