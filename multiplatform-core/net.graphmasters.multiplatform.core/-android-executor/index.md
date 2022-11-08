---
title: AndroidExecutor
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core](../index.html)/[AndroidExecutor](index.html)



# AndroidExecutor



[android]\
class [AndroidExecutor](index.html)(executorService: [ScheduledExecutorService](https://developer.android.com/reference/kotlin/java/util/concurrent/ScheduledExecutorService.html)) : Executor



## Constructors


| | |
|---|---|
| [AndroidExecutor](-android-executor.html) | [android]<br>fun [AndroidExecutor](-android-executor.html)() |
| [AndroidExecutor](-android-executor.html) | [android]<br>fun [AndroidExecutor](-android-executor.html)(threadName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [AndroidExecutor](-android-executor.html) | [android]<br>fun [AndroidExecutor](-android-executor.html)(executorService: [ScheduledExecutorService](https://developer.android.com/reference/kotlin/java/util/concurrent/ScheduledExecutorService.html)) |


## Functions


| Name | Summary |
|---|---|
| [execute](execute.html) | [android]<br>open override fun [execute](execute.html)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [executeDelayed](execute-delayed.html) | [android]<br>open override fun [executeDelayed](execute-delayed.html)(delay: Duration, block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Executor.Future |
| [runOnUiThread](run-on-ui-thread.html) | [android]<br>open override fun [runOnUiThread](run-on-ui-thread.html)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [schedule](schedule.html) | [android]<br>open override fun [schedule](schedule.html)(updateRate: Duration, block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Executor.Future |

