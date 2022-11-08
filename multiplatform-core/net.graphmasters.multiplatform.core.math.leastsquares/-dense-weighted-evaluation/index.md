//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.leastsquares](../index.md)/[DenseWeightedEvaluation](index.md)

# DenseWeightedEvaluation

[common]\
class [DenseWeightedEvaluation](index.md)(unweighted: [LeastSquaresProblem.Evaluation](../-least-squares-problem/-evaluation/index.md), weightSqrt: [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.md)) : [AbstractEvaluation](../-abstract-evaluation/index.md)

## Constructors

| | |
|---|---|
| [DenseWeightedEvaluation](-dense-weighted-evaluation.md) | [common]<br>fun [DenseWeightedEvaluation](-dense-weighted-evaluation.md)(unweighted: [LeastSquaresProblem.Evaluation](../-least-squares-problem/-evaluation/index.md), weightSqrt: [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [getCost](../-abstract-evaluation/get-cost.md) | [common]<br>open override fun [getCost](../-abstract-evaluation/get-cost.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCovariances](../-abstract-evaluation/get-covariances.md) | [common]<br>open override fun [getCovariances](../-abstract-evaluation/get-covariances.md)(threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.md) |
| [getJacobian](get-jacobian.md) | [common]<br>open override fun [getJacobian](get-jacobian.md)(): [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.md) |
| [getPoint](get-point.md) | [common]<br>open override fun [getPoint](get-point.md)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |
| [getResiduals](get-residuals.md) | [common]<br>open override fun [getResiduals](get-residuals.md)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |
| [getRMS](../-abstract-evaluation/get-r-m-s.md) | [common]<br>open override fun [getRMS](../-abstract-evaluation/get-r-m-s.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getSigma](../-abstract-evaluation/get-sigma.md) | [common]<br>open override fun [getSigma](../-abstract-evaluation/get-sigma.md)(covarianceSingularityThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |
