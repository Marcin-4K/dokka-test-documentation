---
title: LocalLeastSquaresProblem
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.math.leastsquares](../index.html)/[LocalLeastSquaresProblem](index.html)



# LocalLeastSquaresProblem



[common]\
class [LocalLeastSquaresProblem](index.html)(model: [MultivariateJacobianFunction](../-multivariate-jacobian-function/index.html), target: [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html), start: [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html), maxEvaluations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), maxIterations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [AbstractOptimizationProblem](../../net.graphmasters.multiplatform.core.math.optim/-abstract-optimization-problem/index.html)&lt;[LeastSquaresProblem.Evaluation](../-least-squares-problem/-evaluation/index.html)&gt; , [LeastSquaresProblem](../-least-squares-problem/index.html)



## Constructors


| | |
|---|---|
| [LocalLeastSquaresProblem](-local-least-squares-problem.html) | [common]<br>fun [LocalLeastSquaresProblem](-local-least-squares-problem.html)(model: [MultivariateJacobianFunction](../-multivariate-jacobian-function/index.html), target: [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html), start: [RealVector](../../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html), maxEvaluations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), maxIterations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


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
| [evaluationCounter](../../net.graphmasters.multiplatform.core.math.optim/-abstract-optimization-problem/evaluation-counter.html) | [common]<br>open override val [evaluationCounter](../../net.graphmasters.multiplatform.core.math.optim/-abstract-optimization-problem/evaluation-counter.html): [Incrementor](../../net.graphmasters.multiplatform.core.math.utils/-incrementor/index.html) |
| [iterationCounter](../../net.graphmasters.multiplatform.core.math.optim/-abstract-optimization-problem/iteration-counter.html) | [common]<br>open override val [iterationCounter](../../net.graphmasters.multiplatform.core.math.optim/-abstract-optimization-problem/iteration-counter.html): [Incrementor](../../net.graphmasters.multiplatform.core.math.utils/-incrementor/index.html) |

