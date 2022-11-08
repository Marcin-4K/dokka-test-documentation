---
title: LeastSquaresProblem
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.math.leastsquares](../index.html)/[LeastSquaresProblem](index.html)



# LeastSquaresProblem



[common]\
interface [LeastSquaresProblem](index.html) : [OptimizationProblem](../../net.graphmasters.multiplatform.core.math.optim/-optimization-problem/index.html)&lt;[LeastSquaresProblem.Evaluation](-evaluation/index.html)&gt;



## Types


| Name | Summary |
|---|---|
| [Evaluation](-evaluation/index.html) | [common]<br>interface [Evaluation](-evaluation/index.html) |


## Functions


| Name | Summary |
|---|---|
| [evaluate](evaluate.html) | [common]<br>abstract fun [evaluate](evaluate.html)(point: [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html)): [LeastSquaresProblem.Evaluation](-evaluation/index.html) |
| [getObservationSize](get-observation-size.html) | [common]<br>abstract fun [getObservationSize](get-observation-size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getParameterSize](get-parameter-size.html) | [common]<br>abstract fun [getParameterSize](get-parameter-size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getStart](get-start.html) | [common]<br>abstract fun [getStart](get-start.html)(): [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html) |


## Properties


| Name | Summary |
|---|---|
| [evaluationCounter](../../net.graphmasters.multiplatform.core.math.optim/-optimization-problem/evaluation-counter.html) | [common]<br>abstract val [evaluationCounter](../../net.graphmasters.multiplatform.core.math.optim/-optimization-problem/evaluation-counter.html): [Incrementor](../../net.graphmasters.multiplatform.core.math.utils/-incrementor/index.html) |
| [iterationCounter](../../net.graphmasters.multiplatform.core.math.optim/-optimization-problem/iteration-counter.html) | [common]<br>abstract val [iterationCounter](../../net.graphmasters.multiplatform.core.math.optim/-optimization-problem/iteration-counter.html): [Incrementor](../../net.graphmasters.multiplatform.core.math.utils/-incrementor/index.html) |


## Inheritors


| Name |
|---|
| [LeastSquaresAdapter](../-least-squares-adapter/index.html) |
| [LocalLeastSquaresProblem](../-local-least-squares-problem/index.html) |

