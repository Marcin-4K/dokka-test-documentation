//[multiplatform-core](../../../../index.md)/[net.graphmasters.multiplatform.core.math.leastsquares](../../index.md)/[LeastSquaresProblem](../index.md)/[Evaluation](index.md)

# Evaluation

[common]\
interface [Evaluation](index.md)

## Functions

| Name | Summary |
|---|---|
| [getCost](get-cost.md) | [common]<br>abstract fun [getCost](get-cost.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCovariances](get-covariances.md) | [common]<br>abstract fun [getCovariances](get-covariances.md)(threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](../../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.md) |
| [getJacobian](get-jacobian.md) | [common]<br>abstract fun [getJacobian](get-jacobian.md)(): [RealMatrix](../../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.md) |
| [getPoint](get-point.md) | [common]<br>abstract fun [getPoint](get-point.md)(): [RealVector](../../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |
| [getResiduals](get-residuals.md) | [common]<br>abstract fun [getResiduals](get-residuals.md)(): [RealVector](../../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |
| [getRMS](get-r-m-s.md) | [common]<br>abstract fun [getRMS](get-r-m-s.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getSigma](get-sigma.md) | [common]<br>abstract fun [getSigma](get-sigma.md)(covarianceSingularityThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealVector](../../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |

## Inheritors

| Name |
|---|
| [AbstractEvaluation](../../-abstract-evaluation/index.md) |
| [Optimum](../../-least-squares-optimizer/-optimum/index.md) |
