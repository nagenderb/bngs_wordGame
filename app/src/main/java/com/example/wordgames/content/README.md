# content — JSON import and sync

> Placeholder package `com.example.wordgames` — the final `applicationId`/package is TBD (Architecture Design §25, T2). Folder is part of the Phase 0 skeleton; no implementation yet.

`ContentSyncManager`, `ContentImporter`, `ContentEnvelope`, `LevelCodec` (per-game extension point), `ContentValidator`, `ValidationResult`/`ValidationIssue`, `BundledContentLoader`.

Pipeline: download -> validate -> parse -> SQLite transaction. Strict all-or-nothing per game file (Design §7, §8).
