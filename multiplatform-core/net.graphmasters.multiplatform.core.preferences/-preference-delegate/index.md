---
title: PreferenceDelegate
---
//[multiplatform-core](../../../index.html)/[net.graphmasters.multiplatform.core.preferences](../index.html)/[PreferenceDelegate](index.html)



# PreferenceDelegate



[android]\
object [PreferenceDelegate](index.html)



## Functions


| Name | Summary |
|---|---|
| [addOnSharedPreferenceChangeListener](add-on-shared-preference-change-listener.html) | [android]<br>fun [addOnSharedPreferenceChangeListener](add-on-shared-preference-change-listener.html)(onSharedPreferenceChangeListener: [SharedPreferences.OnSharedPreferenceChangeListener](https://developer.android.com/reference/kotlin/android/content/SharedPreferences.OnSharedPreferenceChangeListener.html)) |
| [getBoolean](get-boolean.html) | [android]<br>fun [getBoolean](get-boolean.html)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)stringRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), default: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [getBoolean](get-boolean.html)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), default: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getFloat](get-float.html) | [android]<br>fun [getFloat](get-float.html)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), default: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) = 0.0f): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getInt](get-int.html) | [android]<br>fun [getInt](get-int.html)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)stringRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), default: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>fun [getInt](get-int.html)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), default: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getString](get-string.html) | [android]<br>fun [getString](get-string.html)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)stringRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), default: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?<br>fun [getString](get-string.html)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), default: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [hasValue](has-value.html) | [android]<br>fun [hasValue](has-value.html)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)key: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [hasValue](has-value.html)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [init](init.html) | [android]<br>fun [init](init.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), preferences: [SharedPreferences](https://developer.android.com/reference/kotlin/android/content/SharedPreferences.html)) |
| [putBoolean](put-boolean.html) | [android]<br>fun [putBoolean](put-boolean.html)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)key: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), value: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>fun [putBoolean](put-boolean.html)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [putNumber](put-number.html) | [android]<br>fun [putNumber](put-number.html)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)stringRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), value: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)?)<br>fun [putNumber](put-number.html)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)?) |
| [putString](put-string.html) | [android]<br>fun [putString](put-string.html)(@[StringRes](https://developer.android.com/reference/kotlin/androidx/annotation/StringRes.html)stringRes: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)<br>fun [putString](put-string.html)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |
| [removeOnSharedPreferenceChangeListener](remove-on-shared-preference-change-listener.html) | [android]<br>fun [removeOnSharedPreferenceChangeListener](remove-on-shared-preference-change-listener.html)(onSharedPreferenceChangeListener: [SharedPreferences.OnSharedPreferenceChangeListener](https://developer.android.com/reference/kotlin/android/content/SharedPreferences.OnSharedPreferenceChangeListener.html)) |


## Properties


| Name | Summary |
|---|---|
| [allPreferences](all-preferences.html) | [android]<br>val [allPreferences](all-preferences.html): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |

