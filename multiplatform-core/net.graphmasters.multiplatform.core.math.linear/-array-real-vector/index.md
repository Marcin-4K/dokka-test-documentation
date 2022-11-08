//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.linear](../index.md)/[ArrayRealVector](index.md)

# ArrayRealVector

[common]\
class [ArrayRealVector](index.md)(data: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)) : [RealVector](../-real-vector/index.md)

## Constructors

| | |
|---|---|
| [ArrayRealVector](-array-real-vector.md) | [common]<br>fun [ArrayRealVector](-array-real-vector.md)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [ArrayRealVector](-array-real-vector.md) | [common]<br>fun [ArrayRealVector](-array-real-vector.md)(v: [RealVector](../-real-vector/index.md)) |
| [ArrayRealVector](-array-real-vector.md) | [common]<br>fun [ArrayRealVector](-array-real-vector.md)(v: [ArrayRealVector](index.md)) |
| [ArrayRealVector](-array-real-vector.md) | [common]<br>fun [ArrayRealVector](-array-real-vector.md)(data: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)) |

## Functions

| Name | Summary |
|---|---|
| [checkIndex](../-real-vector/check-index.md) | [common]<br>fun [checkIndex](../-real-vector/check-index.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [copy](copy.md) | [common]<br>open override fun [copy](copy.md)(): [ArrayRealVector](index.md) |
| [dotProduct](../-real-vector/dot-product.md) | [common]<br>fun [dotProduct](../-real-vector/dot-product.md)(v: [RealVector](../-real-vector/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getDataRef](get-data-ref.md) | [common]<br>fun [getDataRef](get-data-ref.md)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [getDimension](get-dimension.md) | [common]<br>open override fun [getDimension](get-dimension.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getEntry](get-entry.md) | [common]<br>open override fun [getEntry](get-entry.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [setEntry](set-entry.md) | [common]<br>open override fun [setEntry](set-entry.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [subtract](../-real-vector/subtract.md) | [common]<br>fun [subtract](../-real-vector/subtract.md)(v: [RealVector](../-real-vector/index.md)): [RealVector](../-real-vector/index.md) |
| [toArray](../-real-vector/to-array.md) | [common]<br>fun [toArray](../-real-vector/to-array.md)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
