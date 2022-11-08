---
title: OperationQueueExecutor
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core](../index.html)/[OperationQueueExecutor](index.html)



# OperationQueueExecutor



[ios]\
class [OperationQueueExecutor](index.html) : Executor



## Constructors


| | |
|---|---|
| [OperationQueueExecutor](-operation-queue-executor.html) | [ios]<br>fun [OperationQueueExecutor](-operation-queue-executor.html)() |


## Functions


| Name | Summary |
|---|---|
| [execute](execute.html) | [ios]<br>open override fun [execute](execute.html)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [executeDelayed](execute-delayed.html) | [ios]<br>open override fun [executeDelayed](execute-delayed.html)(delay: [Duration](../../net.graphmasters.multiplatform.core.units/-duration/index.html#294327114%2FExtensions%2F-708110912), block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Executor.Future |
| [runOnUiThread](run-on-ui-thread.html) | [ios]<br>open override fun [runOnUiThread](run-on-ui-thread.html)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [schedule](schedule.html) | [ios]<br>open override fun [schedule](schedule.html)(updateRate: [Duration](../../net.graphmasters.multiplatform.core.units/-duration/index.html#294327114%2FExtensions%2F-708110912), block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Executor.Future |

