# Android-CardView
![Card Design Capture](https://user-images.githubusercontent.com/3745464/100521541-6b670300-31ca-11eb-99a4-4a756e985ef0.PNG)

Before you can use a Material card, you need to add a dependency to the Material Components for Android library.
# Implementation

    implementation 'com.google.android.material:material:1.0.0'
    implementation 'androidx.cardview:cardview:1.0.0'
    
# Material Components Cards
Cards contain content and actions about a single subject.

**Depend on our library**
Material Components for Android is available through Google's Maven Repository. To use it:

Open the **_build.gradle_** file for your application.

Make sure that the repositories section includes Google's Maven Repository google(). For example:

```
  allprojects {
    repositories {
      google()
      jcenter()
    }
  }
```
Add the library to the dependencies section:

```
  dependencies {
    // ...
    implementation 'com.google.android.material:material:<version>'
    // ...
  }
```
Visit Google's Maven Repository or MVN Repository to find the latest version of the library.
