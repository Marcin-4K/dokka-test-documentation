//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.leastsquares](../index.md)/[LeastSquaresProblem](index.md)

# LeastSquaresProblem

[common]\
interface [LeastSquaresProblem](index.md) : [OptimizationProblem](../../net.graphmasters.multiplatform.core.math.optim/-optimization-problem/index.md)&lt;[LeastSquaresProblem.Evaluation](-evaluation/index.md)&gt;

## Types

| Name | Summary |
|---|---|
| [Evaluation](-evaluation/index.md) | [common]<br>interface [Evaluation](-evaluation/index.md) |

## Functions

| Name | Summary |
|---|---|
| [evaluate](evaluate.md) | [common]<br>abstract fun [evaluate](evaluate.md)(point: [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md)): [LeastSquaresProblem.Evaluation](-evaluation/index.md) |
| [getObservationSize](get-observation-size.md) | [common]<br>abstract fun [getObservationSize](get-observation-size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getParameterSize](get-parameter-size.md) | [common]<br>abstract fun [getParameterSize](get-parameter-size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getStart](get-start.md) | [common]<br>abstract fun [getStart](get-start.md)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.md) |

## Properties

| Name | Summary |
|---|---|
| [evaluationCounter](../../net.graphmasters.multiplatform.core.math.optim/-optimization-problem/evaluation-counter.md) | [common]<br>abstract val [evaluationCounter](../../net.graphmasters.multiplatform.core.math.optim/-optimization-problem/evaluation-counter.md): [Incrementor](../../net.graphmasters.multiplatform.core.math.utils/-incrementor/index.md) |
| [iterationCounter](../../net.graphmasters.multiplatform.core.math.optim/-optimization-problem/iteration-counter.md) | [common]<br>abstract val [iterationCounter](../../net.graphmasters.multiplatform.core.math.optim/-optimization-problem/iteration-counter.md): [Incrementor](../../net.graphmasters.multiplatform.core.math.utils/-incrementor/index.md) |

## Inheritors

| Name |
|---|
| [LeastSquaresAdapter](../-least-squares-adapter/index.md) |
| [LocalLeastSquaresProblem](../-local-least-squares-problem/index.md) |
