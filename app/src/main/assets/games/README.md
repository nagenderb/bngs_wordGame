# assets/games

Bundled game content, one folder per language code (`te`, later `hi`, `ta`, `kn`).

Each `gameN.json` has the same shape as the remote file: envelope + file-level `settings` + `levels` (Design §5). At least two levels per game are bundled. They are imported into SQLite on first launch through the normal validate -> transaction pipeline.

**The files in `te/` are illustrative samples** to show structure and exercise the validator. Token values are not content-reviewed. Replace them with real content before release.
