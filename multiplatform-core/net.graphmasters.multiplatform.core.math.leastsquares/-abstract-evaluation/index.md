//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.leastsquares](../index.md)/[AbstractEvaluation](index.md)

# AbstractEvaluation

[common]\
abstract class [AbstractEvaluation](index.md) : [LeastSquaresProblem.Evaluation](../-least-squares-problem/-evaluation/index.md)

## Functions

| Name | Summary |
|---|---|
| [getCost](get-cost.md) | [common]<br>open override fun [getCost](get-cost.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCovariances](get-covariances.md) | [common]<br>open override fun [getCovariances](get-covariances.md)(threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.md) |
| [getJacobian](../-least-squares-problem/-evaluation/get-jacobian.md) | [common]<br>abstract fun [getJacobian](../-least-squares-problem/-evaluation/get-jacobian.md)(): [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.md) |
| [getPoint](../-least-squares-problem/-evaluation/get-point.md) | [common]<br>abstract fun [getPoint](../-least-squares-problem/-evaluation/get-point.md)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |
| [getResiduals](../-least-squares-problem/-evaluation/get-residuals.md) | [common]<br>abstract fun [getResiduals](../-least-squares-problem/-evaluation/get-residuals.md)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |
| [getRMS](get-r-m-s.md) | [common]<br>open override fun [getRMS](get-r-m-s.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getSigma](get-sigma.md) | [common]<br>open override fun [getSigma](get-sigma.md)(covarianceSingularityThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |

## Inheritors

| Name |
|---|
| [DenseWeightedEvaluation](../-dense-weighted-evaluation/index.md) |
