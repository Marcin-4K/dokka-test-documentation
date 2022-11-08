//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core](../index.md)/[JVMExecutor](index.md)

# JVMExecutor

[jvm]\
class [JVMExecutor](index.md) : Executor

## Constructors

| | |
|---|---|
| [JVMExecutor](-j-v-m-executor.md) | [jvm]<br>fun [JVMExecutor](-j-v-m-executor.md)() |

## Functions

| Name | Summary |
|---|---|
| [execute](execute.md) | [jvm]<br>open override fun [execute](execute.md)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [executeDelayed](execute-delayed.md) | [jvm]<br>open override fun [executeDelayed](execute-delayed.md)(delay: Duration, block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Executor.Future |
| [runOnUiThread](run-on-ui-thread.md) | [jvm]<br>open override fun [runOnUiThread](run-on-ui-thread.md)(block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)) |
| [schedule](schedule.md) | [jvm]<br>open override fun [schedule](schedule.md)(updateRate: Duration, block: () -&gt; [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)): Executor.Future |
