# data/dao

> Placeholder package `com.example.wordgames` — the final `applicationId`/package is TBD (Architecture Design §25, T2). Folder is part of the Phase 0 skeleton; no implementation yet.

SQL only, parameterized: `GameDao`, `ContentVersionDao`, `LevelDao`, `SettingsDao`, `Game1LevelDao`, `Game2LevelDao`, `Game3LevelDao`, `Game4LevelDao`, `ProgressDao`, `ImageCacheDao`. DAOs take a `SQLiteDatabase` so the importer can pass the transaction handle.
