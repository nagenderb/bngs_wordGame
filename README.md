# bngs_wordGame — Vini Word Game

Android word-puzzle game for Indian languages (Telugu first; Hindi, Tamil, Kannada planned). **Java only, no Kotlin.** SQLite for runtime content and progress, JSON for remote content, AdMob for ads.

## Status

Phase 0: **architecture and project skeleton only.** No application code yet. See `docs/Software_Architecture_Design_v1.md`.

## Games

1. Word Rearrangement (drag and drop String tokens)
2. Text Question + Answer (24-key keyboard)
3. Image Question + Answer (24-key keyboard)
4. Word Search

## Repository layout

```
docs/                                   architecture and design documents
app/                                    Android application module (see app/README.md)
  src/main/java/com/example/wordgames/  code, one package per architectural area (README in each)
  src/main/assets/config/               app_config.json - deployment configuration only
  src/main/assets/games/<lang>/         bundled sample game JSON (settings + levels)
  src/main/assets/images/<lang>/        bundled Game 3 images
  src/debug/assets/config/              debug config override (test ad IDs)
  src/test/                             JVM unit tests and fixtures
  src/androidTest/                      instrumented tests
```

## Key design rules

- Game content comes from JSON, never hardcoded in Java.
- Per-game settings (keyboards, Game 1 animation, Game 4 rules) live in each game's JSON `settings` block; `app_config.json` is deployment configuration only.
- Language-specific playable units are Java `String` tokens, never `char`.
- Gameplay is offline-first and reads only from SQLite.

## Not yet decided

`applicationId`, `minSdk`/`targetSdk` values, Gradle/AGP versions, home button titles. See the TBD register in the architecture document (section 25).
