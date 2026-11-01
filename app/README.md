# app module

Android application module (Java only, no Kotlin).

```
app/src/main/java/com/example/wordgames   application code (see package READMEs)
app/src/main/assets/config                deployment configuration (app_config.json)
app/src/main/assets/games/<lang>          bundled game JSON (initial + offline content)
app/src/main/assets/images/<lang>         bundled Game 3 images
app/src/main/res                          Android resources
app/src/debug/assets/config               debug override of app_config.json (test ad IDs)
app/src/test                              JVM unit tests
app/src/androidTest                       instrumented tests
```

Not yet created (decisions pending, Architecture Design §25): `build.gradle`, `AndroidManifest.xml`, `applicationId`, `minSdk`/`targetSdk` values, Gradle/AGP versions.
