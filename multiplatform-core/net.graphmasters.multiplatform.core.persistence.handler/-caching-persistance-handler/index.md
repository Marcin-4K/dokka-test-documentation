---
title: CachingPersistanceHandler
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.persistence.handler](../index.html)/[CachingPersistanceHandler](index.html)



# CachingPersistanceHandler



[android]\
class [CachingPersistanceHandler](index.html)(persistenceHandler: [PersistenceHandler](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/index.html)) : [PersistenceHandler](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/index.html)



## Constructors


| | |
|---|---|
| [CachingPersistanceHandler](-caching-persistance-handler.html) | [android]<br>fun [CachingPersistanceHandler](-caching-persistance-handler.html)(persistenceHandler: [PersistenceHandler](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [addOnItemChangedListener](add-on-item-changed-listener.html) | [android]<br>open override fun [addOnItemChangedListener](add-on-item-changed-listener.html)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/-on-item-changed-listener/index.html)) |
| [delete](delete.html) | [android]<br>open override fun [delete](delete.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [hasItem](has-item.html) | [android]<br>open override fun [hasItem](has-item.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [load](load.html) | [android]<br>open override fun &lt;[A](load.html) : [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)&gt; [load](load.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [A](load.html)? |
| [removeOnItemChangedListener](remove-on-item-changed-listener.html) | [android]<br>open override fun [removeOnItemChangedListener](remove-on-item-changed-listener.html)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/-on-item-changed-listener/index.html)) |
| [store](store.html) | [android]<br>open override fun [store](store.html)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), item: [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

