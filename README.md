### Integration

The lib is available on Jitpack, you can find it with Gradle.
In the build.gralde of project:

```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```
In the build.gradle of app:
```
dependencies {
    ...
    implementation 'com.github.dmytrodanylyk.shadow-layout:library:1.0.3'
}
```
