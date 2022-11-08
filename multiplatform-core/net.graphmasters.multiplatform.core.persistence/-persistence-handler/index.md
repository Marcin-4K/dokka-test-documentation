---
title: PersistenceHandler
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.persistence](../index.html)/[PersistenceHandler](index.html)



# PersistenceHandler



[android]\
interface [PersistenceHandler](index.html)



## Types


| Name | Summary |
|---|---|
| [OnItemChangedListener](-on-item-changed-listener/index.html) | [android]<br>interface [OnItemChangedListener](-on-item-changed-listener/index.html) |


## Functions


| Name | Summary |
|---|---|
| [addOnItemChangedListener](add-on-item-changed-listener.html) | [android]<br>abstract fun [addOnItemChangedListener](add-on-item-changed-listener.html)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](-on-item-changed-listener/index.html)) |
| [delete](delete.html) | [android]<br>abstract fun [delete](delete.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [hasItem](has-item.html) | [android]<br>abstract fun [hasItem](has-item.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [load](load.html) | [android]<br>abstract fun &lt;[A](load.html) : [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)&gt; [load](load.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [A](load.html)? |
| [removeOnItemChangedListener](remove-on-item-changed-listener.html) | [android]<br>abstract fun [removeOnItemChangedListener](remove-on-item-changed-listener.html)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](-on-item-changed-listener/index.html)) |
| [store](store.html) | [android]<br>abstract fun [store](store.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), item: [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Inheritors


| Name |
|---|
| [CachingPersistanceHandler](../../net.graphmasters.multiplatform.core.persistence.handler/-caching-persistance-handler/index.html) |
| [PrivateFilePersistanceHandler](../../net.graphmasters.multiplatform.core.persistence.handler/-private-file-persistance-handler/index.html) |

