//[multiplatform-core](../../../index.md)/[net.graphmasters.multiplatform.core.math.leastsquares](../index.md)/[LeastSquaresAdapter](index.md)

# LeastSquaresAdapter

[common]\
open class [LeastSquaresAdapter](index.md)(problem: [LeastSquaresProblem](../-least-squares-problem/index.md)) : [LeastSquaresProblem](../-least-squares-problem/index.md)

## Constructors

| | |
|---|---|
| [LeastSquaresAdapter](-least-squares-adapter.md) | [common]<br>fun [LeastSquaresAdapter](-least-squares-adapter.md)(problem: [LeastSquaresProblem](../-least-squares-problem/index.md)) |

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
| [evaluationCounter](evaluation-counter.md) | [common]<br>open override val [evaluationCounter](evaluation-counter.md): [Incrementor](../../net.graphmasters.multiplatform.core.math.utils/-incrementor/index.md) |
| [iterationCounter](iteration-counter.md) | [common]<br>open override val [iterationCounter](iteration-counter.md): [Incrementor](../../net.graphmasters.multiplatform.core.math.utils/-incrementor/index.md) |
