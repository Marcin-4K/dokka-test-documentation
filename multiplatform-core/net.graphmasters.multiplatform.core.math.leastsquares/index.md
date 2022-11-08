---
title: net.graphmasters.multiplatform.core.math.leastsquares
---
//[multiplatform-core](../../index.html)/[net.graphmasters.multiplatform.core.math.leastsquares](index.html)



# Package net.graphmasters.multiplatform.core.math.leastsquares



## Types


| Name | Summary |
|---|---|
| [AbstractEvaluation](-abstract-evaluation/index.html) | [common]<br>abstract class [AbstractEvaluation](-abstract-evaluation/index.html) : [LeastSquaresProblem.Evaluation](-least-squares-problem/-evaluation/index.html) |
| [DenseWeightedEvaluation](-dense-weighted-evaluation/index.html) | [common]<br>class [DenseWeightedEvaluation](-dense-weighted-evaluation/index.html)(unweighted: [LeastSquaresProblem.Evaluation](-least-squares-problem/-evaluation/index.html), weightSqrt: [RealMatrix](../net.graphmasters.multiplatform.core.math.linear/-real-matrix/index.html)) : [AbstractEvaluation](-abstract-evaluation/index.html) |
| [LeastSquaresAdapter](-least-squares-adapter/index.html) | [common]<br>open class [LeastSquaresAdapter](-least-squares-adapter/index.html)(problem: [LeastSquaresProblem](-least-squares-problem/index.html)) : [LeastSquaresProblem](-least-squares-problem/index.html) |
| [LeastSquaresFactory](-least-squares-factory/index.html) | [common]<br>class [LeastSquaresFactory](-least-squares-factory/index.html) |
| [LeastSquaresOptimizer](-least-squares-optimizer/index.html) | [common]<br>interface [LeastSquaresOptimizer](-least-squares-optimizer/index.html) |
| [LeastSquaresProblem](-least-squares-problem/index.html) | [common]<br>interface [LeastSquaresProblem](-least-squares-problem/index.html) : [OptimizationProblem](../net.graphmasters.multiplatform.core.math.optim/-optimization-problem/index.html)&lt;[LeastSquaresProblem.Evaluation](-least-squares-problem/-evaluation/index.html)&gt; |
| [LevenbergMarquardtOptimizer](-levenberg-marquardt-optimizer/index.html) | [common]<br>class [LevenbergMarquardtOptimizer](-levenberg-marquardt-optimizer/index.html)@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)constructor(initialStepBoundFactor: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 100.0, costRelativeTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, parameterRelativeTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, orthoTolerance: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 1.0E-10, rankingThreshold: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = Precision.SAFE_MIN) : [LeastSquaresOptimizer](-least-squares-optimizer/index.html) |
| [LocalLeastSquaresProblem](-local-least-squares-problem/index.html) | [common]<br>class [LocalLeastSquaresProblem](-local-least-squares-problem/index.html)(model: [MultivariateJacobianFunction](-multivariate-jacobian-function/index.html), target: [RealVector](../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html), start: [RealVector](../net.graphmasters.multiplatform.core.math.linear/-real-vector/index.html), maxEvaluations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), maxIterations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [AbstractOptimizationProblem](../net.graphmasters.multiplatform.core.math.optim/-abstract-optimization-problem/index.html)&lt;[LeastSquaresProblem.Evaluation](-least-squares-problem/-evaluation/index.html)&gt; , [LeastSquaresProblem](-least-squares-problem/index.html) |
| [MultivariateJacobianFunction](-multivariate-jacobian-function/index.html) | [common]<br>interface [MultivariateJacobianFunction](-multivariate-jacobian-function/index.html) |
| [OptimumImpl](-optimum-impl/index.html) | [common]<br>class [OptimumImpl](-optimum-impl/index.html)(value: [LeastSquaresProblem.Evaluation](-least-squares-problem/-evaluation/index.html), evaluations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), iterations: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [LeastSquaresOptimizer.Optimum](-least-squares-optimizer/-optimum/index.html) |
| [Precision](-precision/index.html) | [common]<br>class [Precision](-precision/index.html) |

