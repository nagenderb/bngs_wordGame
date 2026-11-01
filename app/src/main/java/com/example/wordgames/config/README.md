# config — Deployment configuration

> Placeholder package `com.example.wordgames` — the final `applicationId`/package is TBD (Architecture Design §25, T2). Folder is part of the Phase 0 skeleton; no implementation yet.

`ConfigManager`, `AppConfig`, `LanguageConfig`, `AdConfig`, `SyncConfig`.

Parses `assets/config/app_config.json` once. **Deployment config only** — no keyboards, no animation, no game settings (those live in each game's JSON `settings` block). Design §4.
