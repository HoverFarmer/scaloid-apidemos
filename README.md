# Android ApiDemos rewritten elegantly

A Scala port of well-known ApiDemos for Android. This project demonstrates effectiveness of [Scaloid](https://github.com/pocorall/scaloid/) library.

Using [Scaloid](https://github.com/pocorall/scaloid/), Android apps can be written much simpler. Compare with our [Scala version](https://github.com/pocorall/scaloid-apidemos/blob/master/src/main/java/com/example/android/apis/app/ActionBarDisplayOptions.scala) of `ActionBarDisplayOptions` and original [Java version](http://grepcode.com/file/repository.grepcode.com/java/ext/com.google.android/android-apps/4.1.1_r1/com/example/android/apis/app/ActionBarDisplayOptions.java).


## Prerequisites

* Maven 3.2 or above
* Android SDK Level 16

Scaloid-ApiDemos requires Android API Level 16 or above.
**Please note that Scaloid supports Android API Level 10 or above.**

## How to build

This is a maven project. Issue `mvn package` to build, and `mvn android:deploy` to deploy on your virtual device.

### Roadmap

* **Completely move the code from Java to Scala** <br/>
  Currently, the code did not completely ported into Scala yet.
  
### License

This software is licensed under the [Apache 2 license](http://www.apache.org/licenses/LICENSE-2.0.html).
