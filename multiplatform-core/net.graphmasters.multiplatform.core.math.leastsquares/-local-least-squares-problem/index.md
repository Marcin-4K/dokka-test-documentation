//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.leastsquares](../index.md)/[LocalLeastSquaresProblem](index.md)

# LocalLeastSquaresProblem

[common]\
class [LocalLeastSquaresProblem](index.md)(model: [MultivariateJacobianFunction](../-multivariate-jacobian-function/index.md), target: [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md), start: [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md), maxEvaluations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), maxIterations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [AbstractOptimizationProblem](../../net.graphmasters.multiplatform.core.math.optim/-abstract-optimization-problem/index.md)&lt;[LeastSquaresProblem.Evaluation](../-least-squares-problem/-evaluation/index.md)&gt; , [LeastSquaresProblem](../-least-squares-problem/index.md)

## Constructors

| | |
|---|---|
| [LocalLeastSquaresProblem](-local-least-squares-problem.md) | [common]<br>fun [LocalLeastSquaresProblem](-local-least-squares-problem.md)(model: [MultivariateJacobianFunction](../-multivariate-jacobian-function/index.md), target: [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md), start: [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md), maxEvaluations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), maxIterations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |

## Functions

| Name | Summary |
|---|---|
| [evaluate](evaluate.md) | [common]<br>open override fun [evaluate](evaluate.md)(point: [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md)): [LeastSquaresProblem.Evaluation](../-least-squares-problem/-evaluation/index.md) |
| [getObservationSize](get-observation-size.md) | [common]<br>open override fun [getObservationSize](get-observation-size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getParameterSize](get-parameter-size.md) | [common]<br>open override fun [getParameterSize](get-parameter-size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getStart](get-start.md) | [common]<br>open override fun [getStart](get-start.md)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |

## Properties

| Name | Summary |
|---|---|
| [evaluationCounter](../../net.graphmasters.multiplatform.core.math.optim/-abstract-optimization-problem/evaluation-counter.md) | [common]<br>open override val [evaluationCounter](../../net.graphmasters.multiplatform.core.math.optim/-abstract-optimization-problem/evaluation-counter.md): [Incrementor](../../net.graphmasters.multiplatform.core.math.utils/-incrementor/index.md) |
| [iterationCounter](../../net.graphmasters.multiplatform.core.math.optim/-abstract-optimization-problem/iteration-counter.md) | [common]<br>open override val [iterationCounter](../../net.graphmasters.multiplatform.core.math.optim/-abstract-optimization-problem/iteration-counter.md): [Incrementor](../../net.graphmasters.multiplatform.core.math.utils/-incrementor/index.md) |
