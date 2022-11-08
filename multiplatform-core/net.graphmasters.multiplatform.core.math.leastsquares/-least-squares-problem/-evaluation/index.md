---
title: Evaluation
---
//[multiplatform-core](../../../../index.html)/[net.graphmasters.multiplatform.core.math.leastsquares](../../index.html)/[LeastSquaresProblem](../index.html)/[Evaluation](index.html)



# Evaluation



[common]\
interface [Evaluation](index.html)



## Functions


| Name | Summary |
|---|---|
| [getCost](get-cost.html) | [common]<br>abstract fun [getCost](get-cost.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCovariances](get-covariances.html) | [common]<br>abstract fun [getCovariances](get-covariances.html)(threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](../../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.html) |
| [getJacobian](get-jacobian.html) | [common]<br>abstract fun [getJacobian](get-jacobian.html)(): [RealMatrix](../../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.html) |
| [getPoint](get-point.html) | [common]<br>abstract fun [getPoint](get-point.html)(): [RealVector](../../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |
| [getResiduals](get-residuals.html) | [common]<br>abstract fun [getResiduals](get-residuals.html)(): [RealVector](../../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |
| [getRMS](get-r-m-s.html) | [common]<br>abstract fun [getRMS](get-r-m-s.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getSigma](get-sigma.html) | [common]<br>abstract fun [getSigma](get-sigma.html)(covarianceSingularityThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealVector](../../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |


## Inheritors


| Name |
|---|
| [AbstractEvaluation](../../-abstract-evaluation/index.html) |
| [Optimum](../../-least-squares-optimizer/-optimum/index.html) |

