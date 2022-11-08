//[multiplatform-core](../../../../index.md)/[net.graphmasters.multiplatform.core.math.leastsquares](../../index.md)/[LeastSquaresOptimizer](../index.md)/[Optimum](index.md)

# Optimum

[common]\
interface [Optimum](index.md) : [LeastSquaresProblem.Evaluation](../../-least-squares-problem/-evaluation/index.md)

## Functions

| Name | Summary |
|---|---|
| [getCost](../../-least-squares-problem/-evaluation/get-cost.md) | [common]<br>abstract fun [getCost](../../-least-squares-problem/-evaluation/get-cost.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCovariances](../../-least-squares-problem/-evaluation/get-covariances.md) | [common]<br>abstract fun [getCovariances](../../-least-squares-problem/-evaluation/get-covariances.md)(threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](../../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.md) |
| [getEvaluations](get-evaluations.md) | [common]<br>abstract fun [getEvaluations](get-evaluations.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getIterations](get-iterations.md) | [common]<br>abstract fun [getIterations](get-iterations.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getJacobian](../../-least-squares-problem/-evaluation/get-jacobian.md) | [common]<br>abstract fun [getJacobian](../../-least-squares-problem/-evaluation/get-jacobian.md)(): [RealMatrix](../../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.md) |
| [getPoint](../../-least-squares-problem/-evaluation/get-point.md) | [common]<br>abstract fun [getPoint](../../-least-squares-problem/-evaluation/get-point.md)(): [RealVector](../../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |
| [getResiduals](../../-least-squares-problem/-evaluation/get-residuals.md) | [common]<br>abstract fun [getResiduals](../../-least-squares-problem/-evaluation/get-residuals.md)(): [RealVector](../../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |
| [getRMS](../../-least-squares-problem/-evaluation/get-r-m-s.md) | [common]<br>abstract fun [getRMS](../../-least-squares-problem/-evaluation/get-r-m-s.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getSigma](../../-least-squares-problem/-evaluation/get-sigma.md) | [common]<br>abstract fun [getSigma](../../-least-squares-problem/-evaluation/get-sigma.md)(covarianceSingularityThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealVector](../../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |

## Inheritors

| Name |
|---|
| [OptimumImpl](../../-optimum-impl/index.md) |
