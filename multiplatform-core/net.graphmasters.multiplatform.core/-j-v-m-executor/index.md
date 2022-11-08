---
title: JVMExecutor
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core](../index.html)/[JVMExecutor](index.html)



# JVMExecutor



[jvm]\
class [JVMExecutor](index.html) : Executor



## Constructors


| | |
|---|---|
| [JVMExecutor](-j-v-m-executor.html) | [jvm]<br>fun [JVMExecutor](-j-v-m-executor.html)() |


## Functions


| Name | Summary |
|---|---|
| [execute](execute.html) | [jvm]<br>open override fun [execute](execute.html)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [executeDelayed](execute-delayed.html) | [jvm]<br>open override fun [executeDelayed](execute-delayed.html)(delay: Duration, block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Executor.Future |
| [runOnUiThread](run-on-ui-thread.html) | [jvm]<br>open override fun [runOnUiThread](run-on-ui-thread.html)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [schedule](schedule.html) | [jvm]<br>open override fun [schedule](schedule.html)(updateRate: Duration, block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Executor.Future |

