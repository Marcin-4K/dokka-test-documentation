//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.persistence.handler](../index.md)/[CachingPersistanceHandler](index.md)

# CachingPersistanceHandler

[android]\
class [CachingPersistanceHandler](index.md)(persistenceHandler: [PersistenceHandler](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/index.md)) : [PersistenceHandler](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/index.md)

## Constructors

| | |
|---|---|
| [CachingPersistanceHandler](-caching-persistance-handler.md) | [android]<br>fun [CachingPersistanceHandler](-caching-persistance-handler.md)(persistenceHandler: [PersistenceHandler](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [addOnItemChangedListener](add-on-item-changed-listener.md) | [android]<br>open override fun [addOnItemChangedListener](add-on-item-changed-listener.md)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/-on-item-changed-listener/index.md)) |
| [delete](delete.md) | [android]<br>open override fun [delete](delete.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [hasItem](has-item.md) | [android]<br>open override fun [hasItem](has-item.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [load](load.md) | [android]<br>open override fun &lt;[A](load.md) : [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)&gt; [load](load.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [A](load.md)? |
| [removeOnItemChangedListener](remove-on-item-changed-listener.md) | [android]<br>open override fun [removeOnItemChangedListener](remove-on-item-changed-listener.md)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/-on-item-changed-listener/index.md)) |
| [store](store.md) | [android]<br>open override fun [store](store.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), item: [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
