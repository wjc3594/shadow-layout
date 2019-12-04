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
    implementation 'com.github.wjc3594:shadow-layout:1.0'
}
```
