# app-content
Monthly content packs for iOS apps (Paletta, Lexibite). Public static JSON only — no code, no secrets, no user data.

## Add a new monthly pack
1. Add `<app>/pack-YYYY-MM.json` (same schema as existing packs).
2. Add its entry to `<app>/manifest.json` and bump the top-level `version`.
3. Commit & push. The app auto-releases the pack once that calendar month arrives.

Served at: https://hugoblur-ctrl.github.io/app-content/
