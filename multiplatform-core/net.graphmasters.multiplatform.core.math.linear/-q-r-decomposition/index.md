//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.linear](../index.md)/[QRDecomposition](index.md)

# QRDecomposition

[common]\
open class [QRDecomposition](index.md)(matrix: [RealMatrix](../-real-matrix/index.md), threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0)

## Constructors

| | |
|---|---|
| [QRDecomposition](-q-r-decomposition.md) | [common]<br>fun [QRDecomposition](-q-r-decomposition.md)(matrix: [RealMatrix](../-real-matrix/index.md), threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0) |

## Types

| Name | Summary |
|---|---|
| [Solver](-solver/index.md) | [common]<br>inner class [Solver](-solver/index.md)(qrt: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;, rDiag: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [DecompositionSolver](../-decomposition-solver/index.md) |

## Properties

| Name | Summary |
|---|---|
| [solver](solver.md) | [common]<br>val [solver](solver.md): [DecompositionSolver](../-decomposition-solver/index.md) |
