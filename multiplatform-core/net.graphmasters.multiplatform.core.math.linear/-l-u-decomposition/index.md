//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.linear](../index.md)/[LUDecomposition](index.md)

# LUDecomposition

[common]\
class [LUDecomposition](index.md)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)constructor(matrix: [RealMatrix](../-real-matrix/index.md), singularityThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_TOO_SMALL)

Calculates the LUP-decomposition of a square matrix.

The LUP-decomposition of a matrix A consists of three matrices L, U and P that satisfy: PA = LU. L is lower triangular (with unit diagonal terms), U is upper triangular and P is a permutation matrix. All matrices are mm.

As shown by the presence of the P matrix, this decomposition is implemented using partial pivoting.

This class is based on the class with similar name from the [JAMA](http://math.nist.gov/javanumerics/jama/) library.

- 
   a .getP method has been added,
- 
   the `det` method has been renamed as .getDeterminant,
- 
   the `getDoublePivot` method has been removed (but the int based .getPivot method has been kept),
- 
   the `solve` and `isNonSingular` methods have been replaced by a .getSolver method and the equivalent methods provided by the returned [DecompositionSolver](../-decomposition-solver/index.md).

#### Since

2.0 (changed to concrete class in 3.0)

## See also

common

| | |
|---|---|
| MathWorld | (http://mathworld.wolfram.com/LUDecomposition.html) |
| Wikipedia | (http://en.wikipedia.org/wiki/LU_decomposition) |

## Constructors

| | |
|---|---|
| [LUDecomposition](-l-u-decomposition.md) | [common]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)<br>fun [LUDecomposition](-l-u-decomposition.md)(matrix: [RealMatrix](../-real-matrix/index.md), singularityThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = DEFAULT_TOO_SMALL) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [common]<br>object [Companion](-companion/index.md) |

## Properties

| Name | Summary |
|---|---|
| [solver](solver.md) | [common]<br>val [solver](solver.md): [DecompositionSolver](../-decomposition-solver/index.md)<br>Get a solver for finding the A  X = B solution in exact linear sense. |
