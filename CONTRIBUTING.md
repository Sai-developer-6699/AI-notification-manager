# Contributing

Thanks for your interest in contributing!

## Quick start

- Fork the repository and create a feature branch.
- Keep changes focused and small.
- Run checks locally before opening a PR:

```bash
./gradlew test assembleDebug
```

## Development guidelines

- **Kotlin style**: follow Android Studio defaults; keep formatting consistent.
- **No secrets in git**: do not commit keystores, API keys, tokens, or `local.properties`.
- **Screenshots**: if you update UI, add/refresh screenshots in `pictures/`.

## Pull requests

- Explain the **why** and the user impact.
- Include a short test plan (what you ran / clicked).
- If behavior changes, add or update tests when feasible.

## Reporting issues

If you found a bug, include:

- device/emulator + Android version
- steps to reproduce
- expected vs actual result
- logs (redacted)

