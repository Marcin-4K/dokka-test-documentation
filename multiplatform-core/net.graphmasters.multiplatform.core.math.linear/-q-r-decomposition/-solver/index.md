---
title: Solver
---
//[multiplatform-core](../../../../index.html)/[net.graphmasters.multiplatform.core.math.linear](../../index.html)/[QRDecomposition](../index.html)/[Solver](index.html)



# Solver



[common]\
inner class [Solver](index.html)(qrt: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;, rDiag: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) : [DecompositionSolver](../../-decomposition-solver/index.html)



## Constructors


| | |
|---|---|
| [Solver](-solver.html) | [common]<br>fun [Solver](-solver.html)(qrt: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)&gt;, rDiag: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [solve](solve.html) | [common]<br>open override fun [solve](solve.html)(b: [RealMatrix](../../-real-matrix/index.html)): [RealMatrix](../../-real-matrix/index.html) |


## Properties


| Name | Summary |
|---|---|
| [inverse](inverse.html) | [common]<br>open override val [inverse](inverse.html): [RealMatrix](../../-real-matrix/index.html) |
| [isNonSingular](is-non-singular.html) | [common]<br>open override val [isNonSingular](is-non-singular.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

