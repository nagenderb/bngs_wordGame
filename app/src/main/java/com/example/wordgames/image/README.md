# image — Image download and cache

> Placeholder package `com.example.wordgames` — the final `applicationId`/package is TBD (Architecture Design §25, T2). Folder is part of the Phase 0 skeleton; no implementation yet.

`ImageManager`, `ImageCache` (disk, `getFilesDir()/images`), `ImageMemoryCache` (LruCache), `ImageRequest`. The only code that touches image files and the `image_cache` table. Design §14.
