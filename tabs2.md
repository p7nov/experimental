Apply the Kotlin Gradle plugin by using [the Gradle plugins DSL](https://docs.gradle.org/current/userguide/plugins.html#sec:plugins_block).
The Kotlin Gradle plugin %kotlinVersion% works with Gradle %gradleVersion% and later.

<tabs>

```groovy
plugins {
    id 'org.jetbrains.kotlin.<...>' version '%kotlinVersion%'
}
```

```kotlin
plugins {
    kotlin("<...>") version "%kotlinVersion%"
}
```

</tabs>
