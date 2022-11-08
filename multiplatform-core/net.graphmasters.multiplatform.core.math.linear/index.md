//[multiplatform-core](../../index.md)/[net.graphmasters.multiplatform.core.math.linear](index.md)

# Package net.graphmasters.multiplatform.core.math.linear

## Types

| Name | Summary |
|---|---|
| [AbstractRealMatrix](-abstract-real-matrix/index.md) | [common]<br>abstract class [AbstractRealMatrix](-abstract-real-matrix/index.md)(rows: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columns: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [RealMatrix](-real-matrix/index.md) |
| [AnyMatrix](-any-matrix/index.md) | [common]<br>interface [AnyMatrix](-any-matrix/index.md) |
| [Array2DRowRealMatrix](-array2-d-row-real-matrix/index.md) | [common]<br>class [Array2DRowRealMatrix](-array2-d-row-real-matrix/index.md)(data: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;) : [AbstractRealMatrix](-abstract-real-matrix/index.md) |
| [ArrayRealVector](-array-real-vector/index.md) | [common]<br>class [ArrayRealVector](-array-real-vector/index.md)(data: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)) : [RealVector](-real-vector/index.md) |
| [BlockRealMatrix](-block-real-matrix/index.md) | [common]<br>class [BlockRealMatrix](-block-real-matrix/index.md)(rows: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), columns: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), blocksData: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;) : [AbstractRealMatrix](-abstract-real-matrix/index.md) |
| [DecompositionSolver](-decomposition-solver/index.md) | [common]<br>interface [DecompositionSolver](-decomposition-solver/index.md) |
| [DefaultRealMatrixPreservingVisitor](-default-real-matrix-preserving-visitor/index.md) | [common]<br>open class [DefaultRealMatrixPreservingVisitor](-default-real-matrix-preserving-visitor/index.md) : [RealMatrixPreservingVisitor](-real-matrix-preserving-visitor/index.md) |
| [DiagonalMatrix](-diagonal-matrix/index.md) | [common]<br>class [DiagonalMatrix](-diagonal-matrix/index.md)(data: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)) : [AbstractRealMatrix](-abstract-real-matrix/index.md) |
| [LUDecomposition](-l-u-decomposition/index.md) | [common]<br>class [LUDecomposition](-l-u-decomposition/index.md)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)constructor(matrix: [RealMatrix](-real-matrix/index.md), singularityThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_TOO_SMALL)<br>Calculates the LUP-decomposition of a square matrix. |
| [QRDecomposition](-q-r-decomposition/index.md) | [common]<br>open class [QRDecomposition](-q-r-decomposition/index.md)(matrix: [RealMatrix](-real-matrix/index.md), threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0) |
| [RealMatrix](-real-matrix/index.md) | [common]<br>interface [RealMatrix](-real-matrix/index.md) : [AnyMatrix](-any-matrix/index.md) |
| [RealMatrixPreservingVisitor](-real-matrix-preserving-visitor/index.md) | [common]<br>interface [RealMatrixPreservingVisitor](-real-matrix-preserving-visitor/index.md) |
| [RealVector](-real-vector/index.md) | [common]<br>abstract class [RealVector](-real-vector/index.md) |
