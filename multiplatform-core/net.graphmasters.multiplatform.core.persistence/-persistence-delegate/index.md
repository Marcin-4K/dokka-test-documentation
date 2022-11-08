//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.persistence](../index.md)/[PersistenceDelegate](index.md)

# PersistenceDelegate

[android]\
object [PersistenceDelegate](index.md)

## Functions

| Name | Summary |
|---|---|
| [addOnItemChangedListener](add-on-item-changed-listener.md) | [android]<br>fun [addOnItemChangedListener](add-on-item-changed-listener.md)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](../-persistence-handler/-on-item-changed-listener/index.md)) |
| [delete](delete.md) | [android]<br>fun [delete](delete.md)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)stringRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>fun [delete](delete.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [hasItem](has-item.md) | [android]<br>fun [hasItem](has-item.md)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)stringRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [hasItem](has-item.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [init](init.md) | [android]<br>fun [init](init.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), persistenceProvider: [PersistenceHandler](../-persistence-handler/index.md)) |
| [load](load.md) | [android]<br>fun &lt;[A](load.md)&gt; [load](load.md)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)stringRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [A](load.md)?<br>fun &lt;[A](load.md)&gt; [load](load.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [A](load.md)? |
| [removeOnItemChangedListener](remove-on-item-changed-listener.md) | [android]<br>fun [removeOnItemChangedListener](remove-on-item-changed-listener.md)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](../-persistence-handler/-on-item-changed-listener/index.md)) |
| [store](store.md) | [android]<br>fun [store](store.md)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)stringRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), item: [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [store](store.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), item: [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
