---
title: DenseWeightedEvaluation
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.math.leastsquares](../index.html)/[DenseWeightedEvaluation](index.html)



# DenseWeightedEvaluation



[common]\
class [DenseWeightedEvaluation](index.html)(unweighted: [LeastSquaresProblem.Evaluation](../-least-squares-problem/-evaluation/index.html), weightSqrt: [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.html)) : [AbstractEvaluation](../-abstract-evaluation/index.html)



## Constructors


| | |
|---|---|
| [DenseWeightedEvaluation](-dense-weighted-evaluation.html) | [common]<br>fun [DenseWeightedEvaluation](-dense-weighted-evaluation.html)(unweighted: [LeastSquaresProblem.Evaluation](../-least-squares-problem/-evaluation/index.html), weightSqrt: [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [getCost](../-abstract-evaluation/get-cost.html) | [common]<br>open override fun [getCost](../-abstract-evaluation/get-cost.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCovariances](../-abstract-evaluation/get-covariances.html) | [common]<br>open override fun [getCovariances](../-abstract-evaluation/get-covariances.html)(threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.html) |
| [getJacobian](get-jacobian.html) | [common]<br>open override fun [getJacobian](get-jacobian.html)(): [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.html) |
| [getPoint](get-point.html) | [common]<br>open override fun [getPoint](get-point.html)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |
| [getResiduals](get-residuals.html) | [common]<br>open override fun [getResiduals](get-residuals.html)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |
| [getRMS](../-abstract-evaluation/get-r-m-s.html) | [common]<br>open override fun [getRMS](../-abstract-evaluation/get-r-m-s.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getSigma](../-abstract-evaluation/get-sigma.html) | [common]<br>open override fun [getSigma](../-abstract-evaluation/get-sigma.html)(covarianceSingularityThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |

