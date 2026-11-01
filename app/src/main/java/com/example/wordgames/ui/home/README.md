# ui/home

> Placeholder package `com.example.wordgames` — the final `applicationId`/package is TBD (Architecture Design §25, T2). Folder is part of the Phase 0 skeleton; no implementation yet.

`HomeActivity` — one button per registered `GameModule` (titles are the only hardcoded game content). Requests the game-selection interstitial through `AdManager`, then navigates.
