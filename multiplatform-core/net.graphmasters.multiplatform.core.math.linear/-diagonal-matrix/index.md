//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.linear](../index.md)/[DiagonalMatrix](index.md)

# DiagonalMatrix

[common]\
class [DiagonalMatrix](index.md)(data: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)) : [AbstractRealMatrix](../-abstract-real-matrix/index.md)

## Constructors

| | |
|---|---|
| [DiagonalMatrix](-diagonal-matrix.md) | [common]<br>fun [DiagonalMatrix](-diagonal-matrix.md)(dim: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [DiagonalMatrix](-diagonal-matrix.md) | [common]<br>fun [DiagonalMatrix](-diagonal-matrix.md)(data: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)) |

## Functions

| Name | Summary |
|---|---|
| [add](../-abstract-real-matrix/add.md) | [common]<br>open override fun [add](../-abstract-real-matrix/add.md)(m: [RealMatrix](../-real-matrix/index.md)): [RealMatrix](../-real-matrix/index.md) |
| [copySubMatrix](../-abstract-real-matrix/copy-sub-matrix.md) | [common]<br>open override fun [copySubMatrix](../-abstract-real-matrix/copy-sub-matrix.md)(startRow: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), endRow: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), endColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), destination: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;) |
| [createMatrix](create-matrix.md) | [common]<br>open override fun [createMatrix](create-matrix.md)(rowDimension: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columnDimension: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [RealMatrix](../-real-matrix/index.md) |
| [getColumnDimension](get-column-dimension.md) | [common]<br>open override fun [getColumnDimension](get-column-dimension.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getData](../-abstract-real-matrix/get-data.md) | [common]<br>open override fun [getData](../-abstract-real-matrix/get-data.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt; |
| [getEntry](get-entry.md) | [common]<br>open override fun [getEntry](get-entry.md)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getRowDimension](get-row-dimension.md) | [common]<br>open override fun [getRowDimension](get-row-dimension.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isSquare](../-abstract-real-matrix/is-square.md) | [common]<br>open override fun [isSquare](../-abstract-real-matrix/is-square.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [multiply](multiply.md) | [common]<br>open override fun [multiply](multiply.md)(m: [RealMatrix](../-real-matrix/index.md)): [RealMatrix](../-real-matrix/index.md) |
| [operate](../-abstract-real-matrix/operate.md) | [common]<br>open override fun [operate](../-abstract-real-matrix/operate.md)(v: [RealVector](../-real-vector/index.md)): [RealVector](../-real-vector/index.md) |
| [scalarMultiply](../-abstract-real-matrix/scalar-multiply.md) | [common]<br>open override fun [scalarMultiply](../-abstract-real-matrix/scalar-multiply.md)(d: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](../-real-matrix/index.md) |
| [setEntry](set-entry.md) | [common]<br>open override fun [setEntry](set-entry.md)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setSubMatrix](../-abstract-real-matrix/set-sub-matrix.md) | [common]<br>open fun [setSubMatrix](../-abstract-real-matrix/set-sub-matrix.md)(subMatrix: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;, row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [subtract](../-abstract-real-matrix/subtract.md) | [common]<br>open override fun [subtract](../-abstract-real-matrix/subtract.md)(m: [RealMatrix](../-real-matrix/index.md)): [RealMatrix](../-real-matrix/index.md) |
| [transpose](../-abstract-real-matrix/transpose.md) | [common]<br>open override fun [transpose](../-abstract-real-matrix/transpose.md)(): [RealMatrix](../-real-matrix/index.md) |
| [walkInOptimizedOrder](../-abstract-real-matrix/walk-in-optimized-order.md) | [common]<br>open override fun [walkInOptimizedOrder](../-abstract-real-matrix/walk-in-optimized-order.md)(visitor: [RealMatrixPreservingVisitor](../-real-matrix-preserving-visitor/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
