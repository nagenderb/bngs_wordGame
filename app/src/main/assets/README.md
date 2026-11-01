# assets

Bundled, read-only files shipped inside the APK.

| Folder | Purpose | Changes via |
|---|---|---|
| `config/` | Deployment configuration | App release |
| `games/<lang>/` | Initial/offline game JSON, imported through the same pipeline as remote JSON | App release (superseded at runtime by newer remote versions) |
| `images/<lang>/` | Bundled Game 3 images referenced by `image.asset` | App release |
