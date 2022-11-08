//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.linear](../index.md)/[RealMatrix](index.md)

# RealMatrix

[common]\
interface [RealMatrix](index.md) : [AnyMatrix](../-any-matrix/index.md)

## Functions

| Name | Summary |
|---|---|
| [add](add.md) | [common]<br>abstract fun [add](add.md)(m: [RealMatrix](index.md)): [RealMatrix](index.md) |
| [copySubMatrix](copy-sub-matrix.md) | [common]<br>abstract fun [copySubMatrix](copy-sub-matrix.md)(startRow: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), endRow: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), endColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), destination: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;) |
| [createMatrix](create-matrix.md) | [common]<br>abstract fun [createMatrix](create-matrix.md)(rowDimension: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columnDimension: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [RealMatrix](index.md) |
| [getColumnDimension](../-any-matrix/get-column-dimension.md) | [common]<br>abstract fun [getColumnDimension](../-any-matrix/get-column-dimension.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getData](get-data.md) | [common]<br>abstract fun [getData](get-data.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt; |
| [getEntry](get-entry.md) | [common]<br>abstract fun [getEntry](get-entry.md)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getRowDimension](../-any-matrix/get-row-dimension.md) | [common]<br>abstract fun [getRowDimension](../-any-matrix/get-row-dimension.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isSquare](../-any-matrix/is-square.md) | [common]<br>abstract fun [isSquare](../-any-matrix/is-square.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [multiply](multiply.md) | [common]<br>abstract fun [multiply](multiply.md)(m: [RealMatrix](index.md)): [RealMatrix](index.md) |
| [operate](operate.md) | [common]<br>abstract fun [operate](operate.md)(v: [RealVector](../-real-vector/index.md)): [RealVector](../-real-vector/index.md) |
| [scalarMultiply](scalar-multiply.md) | [common]<br>abstract fun [scalarMultiply](scalar-multiply.md)(d: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](index.md) |
| [setEntry](set-entry.md) | [common]<br>abstract fun [setEntry](set-entry.md)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [subtract](subtract.md) | [common]<br>abstract fun [subtract](subtract.md)(m: [RealMatrix](index.md)): [RealMatrix](index.md) |
| [transpose](transpose.md) | [common]<br>abstract fun [transpose](transpose.md)(): [RealMatrix](index.md) |
| [walkInOptimizedOrder](walk-in-optimized-order.md) | [common]<br>abstract fun [walkInOptimizedOrder](walk-in-optimized-order.md)(visitor: [RealMatrixPreservingVisitor](../-real-matrix-preserving-visitor/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

## Inheritors

| Name |
|---|
| [AbstractRealMatrix](../-abstract-real-matrix/index.md) |
