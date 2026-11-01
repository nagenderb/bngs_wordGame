# data/network

> Placeholder package `com.example.wordgames` — the final `applicationId`/package is TBD (Architecture Design §25, T2). Folder is part of the Phase 0 skeleton; no implementation yet.

`HttpFetcher` (HTTPS only, conditional GET with ETag/Last-Modified, size cap, SHA-256 while streaming) and `FetchResult`. Uses `HttpURLConnection`.
