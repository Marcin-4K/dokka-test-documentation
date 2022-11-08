//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.leastsquares](../index.md)/[LevenbergMarquardtOptimizer](index.md)

# LevenbergMarquardtOptimizer

[common]\
class [LevenbergMarquardtOptimizer](index.md)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)constructor(initialStepBoundFactor: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 100.0, costRelativeTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, parameterRelativeTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, orthoTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, rankingThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = Precision.SAFE_MIN) : [LeastSquaresOptimizer](../-least-squares-optimizer/index.md)

## Constructors

| | |
|---|---|
| [LevenbergMarquardtOptimizer](-levenberg-marquardt-optimizer.md) | [common]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)<br>fun [LevenbergMarquardtOptimizer](-levenberg-marquardt-optimizer.md)(initialStepBoundFactor: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 100.0, costRelativeTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, parameterRelativeTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, orthoTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, rankingThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = Precision.SAFE_MIN) |

## Types

| Name | Summary |
|---|---|
| [Companion](-companion/index.md) | [common]<br>object [Companion](-companion/index.md) |

## Functions

| Name | Summary |
|---|---|
| [optimize](optimize.md) | [common]<br>open override fun [optimize](optimize.md)(leastSquaresProblem: [LeastSquaresProblem](../-least-squares-problem/index.md)): [LeastSquaresOptimizer.Optimum](../-least-squares-optimizer/-optimum/index.md) |
