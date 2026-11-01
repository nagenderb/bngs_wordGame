# game/common

> Placeholder package `com.example.wordgames` — the final `applicationId`/package is TBD (Architecture Design §25, T2). Folder is part of the Phase 0 skeleton; no implementation yet.

Shared contracts and components: `GameModule`, `GameRegistry`, `GameController`, `GameCallbacks`, `LevelResult`, `ScoringPolicy`, `KeyboardGenerator`, `KeyboardLayout`, `KeyboardState`, `TokenSequence`, `AnimationType`.

`KeyboardGenerator` is shared by Games 2 and 3 (Design §11, ADR-012). Pure Java.
