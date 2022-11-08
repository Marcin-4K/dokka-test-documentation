//[multiplatform-core](../../../../index.md)/[net.graphmasters.multiplatform.core.math.linear](../../index.md)/[QRDecomposition](../index.md)/[Solver](index.md)

# Solver

[common]\
inner class [Solver](index.md)(qrt: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;, rDiag: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [DecompositionSolver](../../-decomposition-solver/index.md)

## Constructors

| | |
|---|---|
| [Solver](-solver.md) | [common]<br>fun [Solver](-solver.md)(qrt: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;, rDiag: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |

## Functions

| Name | Summary |
|---|---|
| [solve](solve.md) | [common]<br>open override fun [solve](solve.md)(b: [RealMatrix](../../-real-matrix/index.md)): [RealMatrix](../../-real-matrix/index.md) |

## Properties

| Name | Summary |
|---|---|
| [inverse](inverse.md) | [common]<br>open override val [inverse](inverse.md): [RealMatrix](../../-real-matrix/index.md) |
| [isNonSingular](is-non-singular.md) | [common]<br>open override val [isNonSingular](is-non-singular.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
