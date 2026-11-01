# data/repository

> Placeholder package `com.example.wordgames` — the final `applicationId`/package is TBD (Architecture Design §25, T2). Folder is part of the Phase 0 skeleton; no implementation yet.

`ContentRepository` (levels, headers, counts, `getSettings(gameId)`) and `ProgressRepository` (the only writer of progress; idempotent `completeLevel`). Return immutable models, never `Cursor`.
