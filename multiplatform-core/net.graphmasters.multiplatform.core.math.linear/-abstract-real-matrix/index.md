//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.linear](../index.md)/[AbstractRealMatrix](index.md)

# AbstractRealMatrix

[common]\
abstract class [AbstractRealMatrix](index.md)(rows: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columns: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [RealMatrix](../-real-matrix/index.md)

## Constructors

| | |
|---|---|
| [AbstractRealMatrix](-abstract-real-matrix.md) | [common]<br>fun [AbstractRealMatrix](-abstract-real-matrix.md)(rows: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columns: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [common]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [add](add.md) | [common]<br>open override fun [add](add.md)(m: [RealMatrix](../-real-matrix/index.md)): [RealMatrix](../-real-matrix/index.md) |
| [copySubMatrix](copy-sub-matrix.md) | [common]<br>open override fun [copySubMatrix](copy-sub-matrix.md)(startRow: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), endRow: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), endColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), destination: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;) |
| [createMatrix](create-matrix.md) | [common]<br>abstract override fun [createMatrix](create-matrix.md)(rowDimension: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columnDimension: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [RealMatrix](../-real-matrix/index.md) |
| [getColumnDimension](get-column-dimension.md) | [common]<br>abstract override fun [getColumnDimension](get-column-dimension.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getData](get-data.md) | [common]<br>open override fun [getData](get-data.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt; |
| [getEntry](get-entry.md) | [common]<br>abstract override fun [getEntry](get-entry.md)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getRowDimension](get-row-dimension.md) | [common]<br>abstract override fun [getRowDimension](get-row-dimension.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isSquare](is-square.md) | [common]<br>open override fun [isSquare](is-square.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [multiply](multiply.md) | [common]<br>open override fun [multiply](multiply.md)(m: [RealMatrix](../-real-matrix/index.md)): [RealMatrix](../-real-matrix/index.md) |
| [operate](operate.md) | [common]<br>open override fun [operate](operate.md)(v: [RealVector](../-real-vector/index.md)): [RealVector](../-real-vector/index.md) |
| [scalarMultiply](scalar-multiply.md) | [common]<br>open override fun [scalarMultiply](scalar-multiply.md)(d: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](../-real-matrix/index.md) |
| [setEntry](set-entry.md) | [common]<br>abstract override fun [setEntry](set-entry.md)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setSubMatrix](set-sub-matrix.md) | [common]<br>open fun [setSubMatrix](set-sub-matrix.md)(subMatrix: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;, row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [subtract](subtract.md) | [common]<br>open override fun [subtract](subtract.md)(m: [RealMatrix](../-real-matrix/index.md)): [RealMatrix](../-real-matrix/index.md) |
| [transpose](transpose.md) | [common]<br>open override fun [transpose](transpose.md)(): [RealMatrix](../-real-matrix/index.md) |
| [walkInOptimizedOrder](walk-in-optimized-order.md) | [common]<br>open override fun [walkInOptimizedOrder](walk-in-optimized-order.md)(visitor: [RealMatrixPreservingVisitor](../-real-matrix-preserving-visitor/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

## Inheritors

| Name |
|---|
| [Array2DRowRealMatrix](../-array2-d-row-real-matrix/index.md) |
| [BlockRealMatrix](../-block-real-matrix/index.md) |
| [DiagonalMatrix](../-diagonal-matrix/index.md) |
