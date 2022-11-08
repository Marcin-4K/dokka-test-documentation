---
title: AbstractRealMatrix
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.math.linear](../index.html)/[AbstractRealMatrix](index.html)



# AbstractRealMatrix



[common]\
abstract class [AbstractRealMatrix](index.html)(rows: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columns: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [RealMatrix](../-real-matrix/index.html)



## Constructors


| | |
|---|---|
| [AbstractRealMatrix](-abstract-real-matrix.html) | [common]<br>fun [AbstractRealMatrix](-abstract-real-matrix.html)(rows: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columns: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [common]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [add](add.html) | [common]<br>open override fun [add](add.html)(m: [RealMatrix](../-real-matrix/index.html)): [RealMatrix](../-real-matrix/index.html) |
| [copySubMatrix](copy-sub-matrix.html) | [common]<br>open override fun [copySubMatrix](copy-sub-matrix.html)(startRow: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), endRow: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), endColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), destination: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;) |
| [createMatrix](create-matrix.html) | [common]<br>abstract override fun [createMatrix](create-matrix.html)(rowDimension: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columnDimension: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [RealMatrix](../-real-matrix/index.html) |
| [getColumnDimension](get-column-dimension.html) | [common]<br>abstract override fun [getColumnDimension](get-column-dimension.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getData](get-data.html) | [common]<br>open override fun [getData](get-data.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt; |
| [getEntry](get-entry.html) | [common]<br>abstract override fun [getEntry](get-entry.html)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getRowDimension](get-row-dimension.html) | [common]<br>abstract override fun [getRowDimension](get-row-dimension.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isSquare](is-square.html) | [common]<br>open override fun [isSquare](is-square.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [multiply](multiply.html) | [common]<br>open override fun [multiply](multiply.html)(m: [RealMatrix](../-real-matrix/index.html)): [RealMatrix](../-real-matrix/index.html) |
| [operate](operate.html) | [common]<br>open override fun [operate](operate.html)(v: [RealVector](../-real-vector/index.html)): [RealVector](../-real-vector/index.html) |
| [scalarMultiply](scalar-multiply.html) | [common]<br>open override fun [scalarMultiply](scalar-multiply.html)(d: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](../-real-matrix/index.html) |
| [setEntry](set-entry.html) | [common]<br>abstract override fun [setEntry](set-entry.html)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setSubMatrix](set-sub-matrix.html) | [common]<br>open fun [setSubMatrix](set-sub-matrix.html)(subMatrix: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;, row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [subtract](subtract.html) | [common]<br>open override fun [subtract](subtract.html)(m: [RealMatrix](../-real-matrix/index.html)): [RealMatrix](../-real-matrix/index.html) |
| [transpose](transpose.html) | [common]<br>open override fun [transpose](transpose.html)(): [RealMatrix](../-real-matrix/index.html) |
| [walkInOptimizedOrder](walk-in-optimized-order.html) | [common]<br>open override fun [walkInOptimizedOrder](walk-in-optimized-order.html)(visitor: [RealMatrixPreservingVisitor](../-real-matrix-preserving-visitor/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


## Inheritors


| Name |
|---|
| [Array2DRowRealMatrix](../-array2-d-row-real-matrix/index.html) |
| [BlockRealMatrix](../-block-real-matrix/index.html) |
| [DiagonalMatrix](../-diagonal-matrix/index.html) |

