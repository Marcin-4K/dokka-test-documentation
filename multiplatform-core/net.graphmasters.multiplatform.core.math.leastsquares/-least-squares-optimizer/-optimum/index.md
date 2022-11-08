---
title: Optimum
---
//[multiplatform-core](../../../../index.html)/[net.graphmasters.multiplatform.core.math.leastsquares](../../index.html)/[LeastSquaresOptimizer](../index.html)/[Optimum](index.html)



# Optimum



[common]\
interface [Optimum](index.html) : [LeastSquaresProblem.Evaluation](../../-least-squares-problem/-evaluation/index.html)



## Functions


| Name | Summary |
|---|---|
| [getCost](../../-least-squares-problem/-evaluation/get-cost.html) | [common]<br>abstract fun [getCost](../../-least-squares-problem/-evaluation/get-cost.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCovariances](../../-least-squares-problem/-evaluation/get-covariances.html) | [common]<br>abstract fun [getCovariances](../../-least-squares-problem/-evaluation/get-covariances.html)(threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](../../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.html) |
| [getEvaluations](get-evaluations.html) | [common]<br>abstract fun [getEvaluations](get-evaluations.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getIterations](get-iterations.html) | [common]<br>abstract fun [getIterations](get-iterations.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getJacobian](../../-least-squares-problem/-evaluation/get-jacobian.html) | [common]<br>abstract fun [getJacobian](../../-least-squares-problem/-evaluation/get-jacobian.html)(): [RealMatrix](../../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.html) |
| [getPoint](../../-least-squares-problem/-evaluation/get-point.html) | [common]<br>abstract fun [getPoint](../../-least-squares-problem/-evaluation/get-point.html)(): [RealVector](../../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |
| [getResiduals](../../-least-squares-problem/-evaluation/get-residuals.html) | [common]<br>abstract fun [getResiduals](../../-least-squares-problem/-evaluation/get-residuals.html)(): [RealVector](../../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |
| [getRMS](../../-least-squares-problem/-evaluation/get-r-m-s.html) | [common]<br>abstract fun [getRMS](../../-least-squares-problem/-evaluation/get-r-m-s.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getSigma](../../-least-squares-problem/-evaluation/get-sigma.html) | [common]<br>abstract fun [getSigma](../../-least-squares-problem/-evaluation/get-sigma.html)(covarianceSingularityThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealVector](../../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |


## Inheritors


| Name |
|---|
| [OptimumImpl](../../-optimum-impl/index.html) |

