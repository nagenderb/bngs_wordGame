# test (JVM unit tests)

JUnit 4 tests that run without a device: rules, keyboard generator, JSON validation, progress logic (with fakes), ad policy, and a test that validates every shipped file under `assets/games/**`.

Layout mirrors the main package: `java/com/example/wordgames/...`. Fixtures (valid and deliberately invalid JSON) go in `resources/`. See Design §21.
