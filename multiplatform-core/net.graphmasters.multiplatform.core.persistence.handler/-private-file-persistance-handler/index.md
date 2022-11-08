//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.persistence.handler](../index.md)/[PrivateFilePersistanceHandler](index.md)

# PrivateFilePersistanceHandler

[android]\
class [PrivateFilePersistanceHandler](index.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)) : [PersistenceHandler](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/index.md)

## Constructors

| | |
|---|---|
| [PrivateFilePersistanceHandler](-private-file-persistance-handler.md) | [android]<br>fun [PrivateFilePersistanceHandler](-private-file-persistance-handler.md)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)) |

## Functions

| Name | Summary |
|---|---|
| [addOnItemChangedListener](add-on-item-changed-listener.md) | [android]<br>open override fun [addOnItemChangedListener](add-on-item-changed-listener.md)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/-on-item-changed-listener/index.md)) |
| [delete](delete.md) | [android]<br>open override fun [delete](delete.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [hasItem](has-item.md) | [android]<br>open override fun [hasItem](has-item.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [load](load.md) | [android]<br>open override fun &lt;[A](load.md) : [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)&gt; [load](load.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [A](load.md)? |
| [removeOnItemChangedListener](remove-on-item-changed-listener.md) | [android]<br>open override fun [removeOnItemChangedListener](remove-on-item-changed-listener.md)(onItemChangedListener: [PersistenceHandler.OnItemChangedListener](../../net.graphmasters.multiplatform.core.persistence/-persistence-handler/-on-item-changed-listener/index.md)) |
| [store](store.md) | [android]<br>open override fun [store](store.md)(id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), item: [Serializable](https://developer.android.com/reference/kotlin/java/io/Serializable.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
