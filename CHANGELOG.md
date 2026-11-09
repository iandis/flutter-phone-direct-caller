## 2.3.0
* Align the Android and iOS build setup with the Flutter 3.47 plugin template: compileSdk 36, minSdk 24, JVM 17 for Java and Kotlin, AGP 9.1.0 and Kotlin 2.4.0 in the buildscript, and iOS 15.0
* Stop applying `kotlin-android` and drop the explicit `kotlin-stdlib-jdk7` dependency: Flutter applies Kotlin, or AGP 9 compiles it itself, so the minimum Flutter SDK is now 3.44.0
* Regenerate the example app with Flutter 3.47.9

## 2.2.0
* use Android namespace
* Use the new `openURL` method on iOS

## 2.1.1
* Closes [#19](https://github.com/yanisalfian/flutter-phone-direct-caller/issues/19) 

## 2.1.0
* Closes [#16](https://github.com/yanisalfian/flutter-phone-direct-caller/issues/16)
* Closes [#12](https://github.com/yanisalfian/flutter-phone-direct-caller/issues/12)
* Closes [#13](https://github.com/yanisalfian/flutter-phone-direct-caller/issues/13)

## 2.0.0
* null safety

## 1.0.1

* Initial release.
* Migration to AndroidX
