---
title: Cartesian
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.geodesy](../index.html)/[Cartesian](index.html)



# Cartesian



[common]\
object [Cartesian](index.html)



## Functions


| Name | Summary |
|---|---|
| [add](add.html) | [common]<br>fun [add](add.html)(vectorA: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), vectorB: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)<br>Adds two vectors. |
| [distanceFromPointToLine](distance-from-point-to-line.html) | [common]<br>fun [distanceFromPointToLine](distance-from-point-to-line.html)(point: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), linePointA: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), linePointB: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The shortest Euclidean distance between a point and a straight line (defined by two points). |
| [distanceFromPointToSegment](distance-from-point-to-segment.html) | [common]<br>fun [distanceFromPointToSegment](distance-from-point-to-segment.html)(point: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), linePointA: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), linePointB: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [distancePointToPoint](distance-point-to-point.html) | [common]<br>fun [distancePointToPoint](distance-point-to-point.html)(pointA: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), pointB: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Euclidean distance between two points. |
| [dotProduct](dot-product.html) | [common]<br>fun [dotProduct](dot-product.html)(vectorA: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), vectorB: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>The dot product of two vectors |
| [intersection2d](intersection2d.html) | [common]<br>fun [intersection2d](intersection2d.html)(p0: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), p1: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), p2: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), p3: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)? |
| [norm](norm.html) | [common]<br>fun [norm](norm.html)(vector: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Computes the Euclidean distance/norm (a.k.a. 2-norm) of a vector. |
| [projectPointOntoLine](project-point-onto-line.html) | [common]<br>fun [projectPointOntoLine](project-point-onto-line.html)(point: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), linePointA: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), linePointB: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)<br>Projects a point onto a straight line (defined by two points). |
| [projectPointOntoSegment](project-point-onto-segment.html) | [common]<br>fun [projectPointOntoSegment](project-point-onto-segment.html)(point: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), linePointA: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), linePointB: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html) |
| [projectVectorOntoVector](project-vector-onto-vector.html) | [common]<br>fun [projectVectorOntoVector](project-vector-onto-vector.html)(vectorA: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), vectorB: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)<br>Projects a vector onto another vector. |
| [scale](scale.html) | [common]<br>fun [scale](scale.html)(scalar: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), vector: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)<br>Scales a vector. |
| [subtract](subtract.html) | [common]<br>fun [subtract](subtract.html)(vectorA: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html), vectorB: [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)): [DoubleArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double-array/index.html)<br>Subtracts one vector from another |

