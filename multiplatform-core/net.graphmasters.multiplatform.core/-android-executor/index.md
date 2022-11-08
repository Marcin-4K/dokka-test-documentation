//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core](../index.md)/[AndroidExecutor](index.md)

# AndroidExecutor

[android]\
class [AndroidExecutor](index.md)(executorService: [ScheduledExecutorService](https://developer.android.com/reference/kotlin/java/util/concurrent/ScheduledExecutorService.html)) : Executor

## Constructors

| | |
|---|---|
| [AndroidExecutor](-android-executor.md) | [android]<br>fun [AndroidExecutor](-android-executor.md)() |
| [AndroidExecutor](-android-executor.md) | [android]<br>fun [AndroidExecutor](-android-executor.md)(threadName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [AndroidExecutor](-android-executor.md) | [android]<br>fun [AndroidExecutor](-android-executor.md)(executorService: [ScheduledExecutorService](https://developer.android.com/reference/kotlin/java/util/concurrent/ScheduledExecutorService.html)) |

## Functions

| Name | Summary |
|---|---|
| [execute](execute.md) | [android]<br>open override fun [execute](execute.md)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [executeDelayed](execute-delayed.md) | [android]<br>open override fun [executeDelayed](execute-delayed.md)(delay: Duration, block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Executor.Future |
| [runOnUiThread](run-on-ui-thread.md) | [android]<br>open override fun [runOnUiThread](run-on-ui-thread.md)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [schedule](schedule.md) | [android]<br>open override fun [schedule](schedule.md)(updateRate: Duration, block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Executor.Future |
