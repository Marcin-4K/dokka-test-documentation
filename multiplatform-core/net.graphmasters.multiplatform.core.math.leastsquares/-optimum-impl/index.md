---
title: OptimumImpl
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.math.leastsquares](../index.html)/[OptimumImpl](index.html)



# OptimumImpl



[common]\
class [OptimumImpl](index.html)(value: [LeastSquaresProblem.Evaluation](../-least-squares-problem/-evaluation/index.html), evaluations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), iterations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [LeastSquaresOptimizer.Optimum](../-least-squares-optimizer/-optimum/index.html)



## Constructors


| | |
|---|---|
| [OptimumImpl](-optimum-impl.html) | [common]<br>fun [OptimumImpl](-optimum-impl.html)(value: [LeastSquaresProblem.Evaluation](../-least-squares-problem/-evaluation/index.html), evaluations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), iterations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [getCost](get-cost.html) | [common]<br>open override fun [getCost](get-cost.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCovariances](get-covariances.html) | [common]<br>open override fun [getCovariances](get-covariances.html)(threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.html) |
| [getEvaluations](get-evaluations.html) | [common]<br>open override fun [getEvaluations](get-evaluations.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getIterations](get-iterations.html) | [common]<br>open override fun [getIterations](get-iterations.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getJacobian](get-jacobian.html) | [common]<br>open override fun [getJacobian](get-jacobian.html)(): [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.html) |
| [getPoint](get-point.html) | [common]<br>open override fun [getPoint](get-point.html)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |
| [getResiduals](get-residuals.html) | [common]<br>open override fun [getResiduals](get-residuals.html)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |
| [getRMS](get-r-m-s.html) | [common]<br>open override fun [getRMS](get-r-m-s.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getSigma](get-sigma.html) | [common]<br>open override fun [getSigma](get-sigma.html)(covarianceSingularityThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |

