//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.persistence](../index.md)/[PersistenceHandler](index.md)

# PersistenceHandler

[android]\
interface [PersistenceHandler](index.md)

## Types

| Name | Summary |
|---|---|
| [OnItemChangedListener](-on-item-changed-listener/index.md) | [android]<br>interface [OnItemChangedListener](-on-item-changed-listener/index.md) |

## Functions

| Name | Summary |
|---|---|
| [addOnItemChangedListener](add-on-item-changed-listener.md) | [android]<br>abstract fun [addOnItemChangedListener](add-on-item-changed-listener.md)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](-on-item-changed-listener/index.md)) |
| [delete](delete.md) | [android]<br>abstract fun [delete](delete.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [hasItem](has-item.md) | [android]<br>abstract fun [hasItem](has-item.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [load](load.md) | [android]<br>abstract fun &lt;[A](load.md) : [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)&gt; [load](load.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [A](load.md)? |
| [removeOnItemChangedListener](remove-on-item-changed-listener.md) | [android]<br>abstract fun [removeOnItemChangedListener](remove-on-item-changed-listener.md)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](-on-item-changed-listener/index.md)) |
| [store](store.md) | [android]<br>abstract fun [store](store.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), item: [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Inheritors

| Name |
|---|
| [CachingPersistanceHandler](../../net.graphmasters.multiplatform.core.persistence.handler/-caching-persistance-handler/index.md) |
| [PrivateFilePersistanceHandler](../../net.graphmasters.multiplatform.core.persistence.handler/-private-file-persistance-handler/index.md) |
