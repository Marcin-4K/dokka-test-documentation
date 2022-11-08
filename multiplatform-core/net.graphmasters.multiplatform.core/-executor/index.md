---
title: Executor
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core](../index.html)/[Executor](index.html)



# Executor



[common]\
interface [Executor](index.html)



## Types


| Name | Summary |
|---|---|
| [Future](-future/index.html) | [common]<br>interface [Future](-future/index.html) |


## Functions


| Name | Summary |
|---|---|
| [execute](execute.html) | [common]<br>abstract fun [execute](execute.html)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [executeDelayed](execute-delayed.html) | [common]<br>abstract fun [executeDelayed](execute-delayed.html)(delay: [Duration](../../net.graphmasters.multiplatform.core.units/-duration/index.html), block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [Executor.Future](-future/index.html) |
| [runOnUiThread](run-on-ui-thread.html) | [common]<br>~~abstract~~ ~~fun~~ [~~runOnUiThread~~](run-on-ui-thread.html)~~(~~block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)~~)~~ |
| [schedule](schedule.html) | [common]<br>abstract fun [schedule](schedule.html)(updateRate: [Duration](../../net.graphmasters.multiplatform.core.units/-duration/index.html), block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): [Executor.Future](-future/index.html) |


## Inheritors


| Name |
|---|
| [AndroidExecutor](../-android-executor/index.html) |
| [OperationQueueExecutor](../-operation-queue-executor/index.html) |
| [JVMExecutor](../-j-v-m-executor/index.html) |

