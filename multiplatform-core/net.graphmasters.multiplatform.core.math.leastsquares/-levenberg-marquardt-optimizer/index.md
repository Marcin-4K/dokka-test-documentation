---
title: LevenbergMarquardtOptimizer
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.math.leastsquares](../index.html)/[LevenbergMarquardtOptimizer](index.html)



# LevenbergMarquardtOptimizer



[common]\
class [LevenbergMarquardtOptimizer](index.html)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)constructor(initialStepBoundFactor: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 100.0, costRelativeTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, parameterRelativeTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, orthoTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, rankingThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = Precision.SAFE_MIN) : [LeastSquaresOptimizer](../-least-squares-optimizer/index.html)



## Constructors


| | |
|---|---|
| [LevenbergMarquardtOptimizer](-levenberg-marquardt-optimizer.html) | [common]<br>@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)<br>fun [LevenbergMarquardtOptimizer](-levenberg-marquardt-optimizer.html)(initialStepBoundFactor: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 100.0, costRelativeTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, parameterRelativeTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, orthoTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, rankingThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = Precision.SAFE_MIN) |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [common]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [optimize](optimize.html) | [common]<br>open override fun [optimize](optimize.html)(leastSquaresProblem: [LeastSquaresProblem](../-least-squares-problem/index.html)): [LeastSquaresOptimizer.Optimum](../-least-squares-optimizer/-optimum/index.html) |

