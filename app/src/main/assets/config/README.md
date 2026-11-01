# assets/config

`app_config.json` — **deployment configuration only** (Architecture Design §4.1):

- active language and per-language game JSON URLs
- bundled content path
- AdMob unit IDs, ad cadence and cooldown
- sync parameters and timeouts

It must **not** contain keyboards, the Game 1 animation, Game 4 rules or any level content. Those live in each game's JSON (`settings` block and `levels`).

The AdMob *App ID* is not here; it goes into the manifest via Gradle `manifestPlaceholders`.
The ad unit IDs in this sample are placeholders. Debug builds override this file (`app/src/debug/assets/config/`) with Google's public test IDs.
