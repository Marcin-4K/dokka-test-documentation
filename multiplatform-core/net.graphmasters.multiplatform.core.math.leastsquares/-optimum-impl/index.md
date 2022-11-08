//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.leastsquares](../index.md)/[OptimumImpl](index.md)

# OptimumImpl

[common]\
class [OptimumImpl](index.md)(value: [LeastSquaresProblem.Evaluation](../-least-squares-problem/-evaluation/index.md), evaluations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), iterations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [LeastSquaresOptimizer.Optimum](../-least-squares-optimizer/-optimum/index.md)

## Constructors

| | |
|---|---|
| [OptimumImpl](-optimum-impl.md) | [common]<br>fun [OptimumImpl](-optimum-impl.md)(value: [LeastSquaresProblem.Evaluation](../-least-squares-problem/-evaluation/index.md), evaluations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), iterations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |

## Functions

| Name | Summary |
|---|---|
| [getCost](get-cost.md) | [common]<br>open override fun [getCost](get-cost.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCovariances](get-covariances.md) | [common]<br>open override fun [getCovariances](get-covariances.md)(threshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.md) |
| [getEvaluations](get-evaluations.md) | [common]<br>open override fun [getEvaluations](get-evaluations.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getIterations](get-iterations.md) | [common]<br>open override fun [getIterations](get-iterations.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getJacobian](get-jacobian.md) | [common]<br>open override fun [getJacobian](get-jacobian.md)(): [RealMatrix](../../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.md) |
| [getPoint](get-point.md) | [common]<br>open override fun [getPoint](get-point.md)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |
| [getResiduals](get-residuals.md) | [common]<br>open override fun [getResiduals](get-residuals.md)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |
| [getRMS](get-r-m-s.md) | [common]<br>open override fun [getRMS](get-r-m-s.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getSigma](get-sigma.md) | [common]<br>open override fun [getSigma](get-sigma.md)(covarianceSingularityThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |
