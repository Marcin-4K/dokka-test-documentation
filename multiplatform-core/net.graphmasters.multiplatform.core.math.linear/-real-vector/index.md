//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.linear](../index.md)/[RealVector](index.md)

# RealVector

[common]\
abstract class [RealVector](index.md)

## Constructors

| | |
|---|---|
| [RealVector](-real-vector.md) | [common]<br>fun [RealVector](-real-vector.md)() |

## Functions

| Name | Summary |
|---|---|
| [checkIndex](check-index.md) | [common]<br>fun [checkIndex](check-index.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [copy](copy.md) | [common]<br>abstract fun [copy](copy.md)(): [RealVector](index.md) |
| [dotProduct](dot-product.md) | [common]<br>fun [dotProduct](dot-product.md)(v: [RealVector](index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getDimension](get-dimension.md) | [common]<br>abstract fun [getDimension](get-dimension.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getEntry](get-entry.md) | [common]<br>abstract fun [getEntry](get-entry.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [setEntry](set-entry.md) | [common]<br>abstract fun [setEntry](set-entry.md)(index: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [subtract](subtract.md) | [common]<br>fun [subtract](subtract.md)(v: [RealVector](index.md)): [RealVector](index.md) |
| [toArray](to-array.md) | [common]<br>fun [toArray](to-array.md)(): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |

## Inheritors

| Name |
|---|
| [ArrayRealVector](../-array-real-vector/index.md) |
