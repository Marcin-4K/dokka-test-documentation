---
title: Array2DRowRealMatrix
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.math.linear](../index.html)/[Array2DRowRealMatrix](index.html)



# Array2DRowRealMatrix



[common]\
class [Array2DRowRealMatrix](index.html)(data: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;) : [AbstractRealMatrix](../-abstract-real-matrix/index.html)



## Constructors


| | |
|---|---|
| [Array2DRowRealMatrix](-array2-d-row-real-matrix.html) | [common]<br>fun [Array2DRowRealMatrix](-array2-d-row-real-matrix.html)(rowDimension: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columnDimension: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [Array2DRowRealMatrix](-array2-d-row-real-matrix.html) | [common]<br>fun [Array2DRowRealMatrix](-array2-d-row-real-matrix.html)(data: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;) |


## Functions


| Name | Summary |
|---|---|
| [add](../-abstract-real-matrix/add.html) | [common]<br>open override fun [add](../-abstract-real-matrix/add.html)(m: [RealMatrix](../-real-matrix/index.html)): [RealMatrix](../-real-matrix/index.html) |
| [copySubMatrix](../-abstract-real-matrix/copy-sub-matrix.html) | [common]<br>open override fun [copySubMatrix](../-abstract-real-matrix/copy-sub-matrix.html)(startRow: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), endRow: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), endColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), destination: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;) |
| [createMatrix](create-matrix.html) | [common]<br>open override fun [createMatrix](create-matrix.html)(rowDimension: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columnDimension: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [RealMatrix](../-real-matrix/index.html) |
| [getColumnDimension](get-column-dimension.html) | [common]<br>open override fun [getColumnDimension](get-column-dimension.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getData](get-data.html) | [common]<br>open override fun [getData](get-data.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt; |
| [getEntry](get-entry.html) | [common]<br>open override fun [getEntry](get-entry.html)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getRowDimension](get-row-dimension.html) | [common]<br>open override fun [getRowDimension](get-row-dimension.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isSquare](../-abstract-real-matrix/is-square.html) | [common]<br>open override fun [isSquare](../-abstract-real-matrix/is-square.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [multiply](../-abstract-real-matrix/multiply.html) | [common]<br>open override fun [multiply](../-abstract-real-matrix/multiply.html)(m: [RealMatrix](../-real-matrix/index.html)): [RealMatrix](../-real-matrix/index.html) |
| [operate](../-abstract-real-matrix/operate.html) | [common]<br>open override fun [operate](../-abstract-real-matrix/operate.html)(v: [RealVector](../-real-vector/index.html)): [RealVector](../-real-vector/index.html) |
| [scalarMultiply](../-abstract-real-matrix/scalar-multiply.html) | [common]<br>open override fun [scalarMultiply](../-abstract-real-matrix/scalar-multiply.html)(d: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](../-real-matrix/index.html) |
| [setEntry](set-entry.html) | [common]<br>open override fun [setEntry](set-entry.html)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [setSubMatrix](../-abstract-real-matrix/set-sub-matrix.html) | [common]<br>open fun [setSubMatrix](../-abstract-real-matrix/set-sub-matrix.html)(subMatrix: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;, row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [subtract](../-abstract-real-matrix/subtract.html) | [common]<br>open override fun [subtract](../-abstract-real-matrix/subtract.html)(m: [RealMatrix](../-real-matrix/index.html)): [RealMatrix](../-real-matrix/index.html) |
| [transpose](../-abstract-real-matrix/transpose.html) | [common]<br>open override fun [transpose](../-abstract-real-matrix/transpose.html)(): [RealMatrix](../-real-matrix/index.html) |
| [walkInOptimizedOrder](../-abstract-real-matrix/walk-in-optimized-order.html) | [common]<br>open override fun [walkInOptimizedOrder](../-abstract-real-matrix/walk-in-optimized-order.html)(visitor: [RealMatrixPreservingVisitor](../-real-matrix-preserving-visitor/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

