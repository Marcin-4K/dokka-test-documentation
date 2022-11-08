---
title: LeastSquaresAdapter
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.math.leastsquares](../index.html)/[LeastSquaresAdapter](index.html)



# LeastSquaresAdapter



[common]\
open class [LeastSquaresAdapter](index.html)(problem: [LeastSquaresProblem](../-least-squares-problem/index.html)) : [LeastSquaresProblem](../-least-squares-problem/index.html)



## Constructors


| | |
|---|---|
| [LeastSquaresAdapter](-least-squares-adapter.html) | [common]<br>fun [LeastSquaresAdapter](-least-squares-adapter.html)(problem: [LeastSquaresProblem](../-least-squares-problem/index.html)) |


## Functions


| Name | Summary |
|---|---|
| [evaluate](evaluate.html) | [common]<br>open override fun [evaluate](evaluate.html)(point: [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html)): [LeastSquaresProblem.Evaluation](../-least-squares-problem/-evaluation/index.html) |
| [getObservationSize](get-observation-size.html) | [common]<br>open override fun [getObservationSize](get-observation-size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getParameterSize](get-parameter-size.html) | [common]<br>open override fun [getParameterSize](get-parameter-size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getStart](get-start.html) | [common]<br>open override fun [getStart](get-start.html)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |


## Properties


| Name | Summary |
|---|---|
| [evaluationCounter](evaluation-counter.html) | [common]<br>open override val [evaluationCounter](evaluation-counter.html): [Incrementor](../../net.graphmasters.multiplatform.core.math.utils/-incrementor/index.html) |
| [iterationCounter](iteration-counter.html) | [common]<br>open override val [iterationCounter](iteration-counter.html): [Incrementor](../../net.graphmasters.multiplatform.core.math.utils/-incrementor/index.html) |

