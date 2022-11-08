---
title: PrivateFilePersistanceHandler
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.persistence.handler](../index.html)/[PrivateFilePersistanceHandler](index.html)



# PrivateFilePersistanceHandler



[android]\
class [PrivateFilePersistanceHandler](index.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)) : [PersistenceHandler](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/index.html)



## Constructors


| | |
|---|---|
| [PrivateFilePersistanceHandler](-private-file-persistance-handler.html) | [android]<br>fun [PrivateFilePersistanceHandler](-private-file-persistance-handler.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)) |


## Functions


| Name | Summary |
|---|---|
| [addOnItemChangedListener](add-on-item-changed-listener.html) | [android]<br>open override fun [addOnItemChangedListener](add-on-item-changed-listener.html)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/-on-item-changed-listener/index.html)) |
| [delete](delete.html) | [android]<br>open override fun [delete](delete.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [hasItem](has-item.html) | [android]<br>open override fun [hasItem](has-item.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [load](load.html) | [android]<br>open override fun &lt;[A](load.html) : [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)&gt; [load](load.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [A](load.html)? |
| [removeOnItemChangedListener](remove-on-item-changed-listener.html) | [android]<br>open override fun [removeOnItemChangedListener](remove-on-item-changed-listener.html)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/-on-item-changed-listener/index.html)) |
| [store](store.html) | [android]<br>open override fun [store](store.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), item: [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

