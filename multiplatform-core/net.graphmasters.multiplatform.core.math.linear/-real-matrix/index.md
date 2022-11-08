---
title: RealMatrix
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.math.linear](../index.html)/[RealMatrix](index.html)



# RealMatrix



[common]\
interface [RealMatrix](index.html) : [AnyMatrix](../-any-matrix/index.html)



## Functions


| Name | Summary |
|---|---|
| [add](add.html) | [common]<br>abstract fun [add](add.html)(m: [RealMatrix](index.html)): [RealMatrix](index.html) |
| [copySubMatrix](copy-sub-matrix.html) | [common]<br>abstract fun [copySubMatrix](copy-sub-matrix.html)(startRow: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), endRow: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), endColumn: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), destination: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;) |
| [createMatrix](create-matrix.html) | [common]<br>abstract fun [createMatrix](create-matrix.html)(rowDimension: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columnDimension: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [RealMatrix](index.html) |
| [getColumnDimension](../-any-matrix/get-column-dimension.html) | [common]<br>abstract fun [getColumnDimension](../-any-matrix/get-column-dimension.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getData](get-data.html) | [common]<br>abstract fun [getData](get-data.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt; |
| [getEntry](get-entry.html) | [common]<br>abstract fun [getEntry](get-entry.html)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getRowDimension](../-any-matrix/get-row-dimension.html) | [common]<br>abstract fun [getRowDimension](../-any-matrix/get-row-dimension.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isSquare](../-any-matrix/is-square.html) | [common]<br>abstract fun [isSquare](../-any-matrix/is-square.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [multiply](multiply.html) | [common]<br>abstract fun [multiply](multiply.html)(m: [RealMatrix](index.html)): [RealMatrix](index.html) |
| [operate](operate.html) | [common]<br>abstract fun [operate](operate.html)(v: [RealVector](../-real-vector/index.html)): [RealVector](../-real-vector/index.html) |
| [scalarMultiply](scalar-multiply.html) | [common]<br>abstract fun [scalarMultiply](scalar-multiply.html)(d: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](index.html) |
| [setEntry](set-entry.html) | [common]<br>abstract fun [setEntry](set-entry.html)(row: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), column: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |
| [subtract](subtract.html) | [common]<br>abstract fun [subtract](subtract.html)(m: [RealMatrix](index.html)): [RealMatrix](index.html) |
| [transpose](transpose.html) | [common]<br>abstract fun [transpose](transpose.html)(): [RealMatrix](index.html) |
| [walkInOptimizedOrder](walk-in-optimized-order.html) | [common]<br>abstract fun [walkInOptimizedOrder](walk-in-optimized-order.html)(visitor: [RealMatrixPreservingVisitor](../-real-matrix-preserving-visitor/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |


## Inheritors


| Name |
|---|
| [AbstractRealMatrix](../-abstract-real-matrix/index.html) |

