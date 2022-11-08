---
title: net.graphmasters.multiplatform.core.math.linear
---
//[multiplatform-core](../../index.html)/[net.graphmasters.multiplatform.core.math.linear](index.html)



# Package net.graphmasters.multiplatform.core.math.linear



## Types


| Name | Summary |
|---|---|
| [AbstractRealMatrix](-abstract-real-matrix/index.html) | [common]<br>abstract class [AbstractRealMatrix](-abstract-real-matrix/index.html)(rows: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columns: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [RealMatrix](-real-matrix/index.html) |
| [AnyMatrix](-any-matrix/index.html) | [common]<br>interface [AnyMatrix](-any-matrix/index.html) |
| [Array2DRowRealMatrix](-array2-d-row-real-matrix/index.html) | [common]<br>class [Array2DRowRealMatrix](-array2-d-row-real-matrix/index.html)(data: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;) : [AbstractRealMatrix](-abstract-real-matrix/index.html) |
| [ArrayRealVector](-array-real-vector/index.html) | [common]<br>class [ArrayRealVector](-array-real-vector/index.html)(data: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)) : [RealVector](-real-vector/index.html) |
| [BlockRealMatrix](-block-real-matrix/index.html) | [common]<br>class [BlockRealMatrix](-block-real-matrix/index.html)(rows: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columns: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), blocksData: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;) : [AbstractRealMatrix](-abstract-real-matrix/index.html) |
| [DecompositionSolver](-decomposition-solver/index.html) | [common]<br>interface [DecompositionSolver](-decomposition-solver/index.html) |
| [DefaultRealMatrixPreservingVisitor](-default-real-matrix-preserving-visitor/index.html) | [common]<br>open class [DefaultRealMatrixPreservingVisitor](-default-real-matrix-preserving-visitor/index.html) : [RealMatrixPreservingVisitor](-real-matrix-preserving-visitor/index.html) |
| [DiagonalMatrix](-diagonal-matrix/index.html) | [common]<br>class [DiagonalMatrix](-diagonal-matrix/index.html)(data: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)) : [AbstractRealMatrix](-abstract-real-matrix/index.html) |
| [LUDecomposition](-l-u-decomposition/index.html) | [common]<br>class [LUDecomposition](-l-u-decomposition/index.html)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)constructor(matrix: [RealMatrix](-real-matrix/index.html), singularityThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_TOO_SMALL)<br>Calculates the LUP-decomposition of a square matrix. |
| [QRDecomposition](-q-r-decomposition/index.html) | [common]<br>open class [QRDecomposition](-q-r-decomposition/index.html)(matrix: [RealMatrix](-real-matrix/index.html), threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0) |
| [RealMatrix](-real-matrix/index.html) | [common]<br>interface [RealMatrix](-real-matrix/index.html) : [AnyMatrix](-any-matrix/index.html) |
| [RealMatrixPreservingVisitor](-real-matrix-preserving-visitor/index.html) | [common]<br>interface [RealMatrixPreservingVisitor](-real-matrix-preserving-visitor/index.html) |
| [RealVector](-real-vector/index.html) | [common]<br>abstract class [RealVector](-real-vector/index.html) |

