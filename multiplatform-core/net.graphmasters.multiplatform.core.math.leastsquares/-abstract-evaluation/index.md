---
title: AbstractEvaluation
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.math.leastsquares](../index.html)/[AbstractEvaluation](index.html)



# AbstractEvaluation



[common]\
abstract class [AbstractEvaluation](index.html) : [LeastSquaresProblem.Evaluation](../-least-squares-problem/-evaluation/index.html)



## Functions


| Name | Summary |
|---|---|
| [getCost](get-cost.html) | [common]<br>open override fun [getCost](get-cost.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCovariances](get-covariances.html) | [common]<br>open override fun [getCovariances](get-covariances.html)(threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.html) |
| [getJacobian](../-least-squares-problem/-evaluation/get-jacobian.html) | [common]<br>abstract fun [getJacobian](../-least-squares-problem/-evaluation/get-jacobian.html)(): [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.html) |
| [getPoint](../-least-squares-problem/-evaluation/get-point.html) | [common]<br>abstract fun [getPoint](../-least-squares-problem/-evaluation/get-point.html)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |
| [getResiduals](../-least-squares-problem/-evaluation/get-residuals.html) | [common]<br>abstract fun [getResiduals](../-least-squares-problem/-evaluation/get-residuals.html)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |
| [getRMS](get-r-m-s.html) | [common]<br>open override fun [getRMS](get-r-m-s.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getSigma](get-sigma.html) | [common]<br>open override fun [getSigma](get-sigma.html)(covarianceSingularityThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |


## Inheritors


| Name |
|---|
| [DenseWeightedEvaluation](../-dense-weighted-evaluation/index.html) |

