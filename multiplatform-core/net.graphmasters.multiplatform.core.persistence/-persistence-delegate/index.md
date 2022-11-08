---
title: PersistenceDelegate
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.persistence](../index.html)/[PersistenceDelegate](index.html)



# PersistenceDelegate



[android]\
object [PersistenceDelegate](index.html)



## Functions


| Name | Summary |
|---|---|
| [addOnItemChangedListener](add-on-item-changed-listener.html) | [android]<br>fun [addOnItemChangedListener](add-on-item-changed-listener.html)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](../-persistence-handler/-on-item-changed-listener/index.html)) |
| [delete](delete.html) | [android]<br>fun [delete](delete.html)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)stringRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>fun [delete](delete.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [hasItem](has-item.html) | [android]<br>fun [hasItem](has-item.html)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)stringRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [hasItem](has-item.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [init](init.html) | [android]<br>fun [init](init.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), persistenceProvider: [PersistenceHandler](../-persistence-handler/index.html)) |
| [load](load.html) | [android]<br>fun &lt;[A](load.html)&gt; [load](load.html)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)stringRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [A](load.html)?<br>fun &lt;[A](load.html)&gt; [load](load.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [A](load.html)? |
| [removeOnItemChangedListener](remove-on-item-changed-listener.html) | [android]<br>fun [removeOnItemChangedListener](remove-on-item-changed-listener.html)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](../-persistence-handler/-on-item-changed-listener/index.html)) |
| [store](store.html) | [android]<br>fun [store](store.html)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)stringRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), item: [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [store](store.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), item: [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

