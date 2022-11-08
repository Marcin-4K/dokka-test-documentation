//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.linear](../index.md)/[RealMatrixPreservingVisitor](index.md)

# RealMatrixPreservingVisitor

[common]\
interface [RealMatrixPreservingVisitor](index.md)

## Functions

| Name | Summary |
|---|---|
| [end](end.md) | [common]<br>abstract fun [end](end.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [start](start.md) | [common]<br>abstract fun [start](start.md)(rows: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columns: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startRow: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), endRow: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), endColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [visit](visit.md) | [common]<br>abstract fun [visit](visit.md)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Inheritors

| Name |
|---|
| [DefaultRealMatrixPreservingVisitor](../-default-real-matrix-preserving-visitor/index.md) |
