# haiku — AGENTS.md

## Commands
- `flutter run` — run on device/emulator
- `flutter test` — run all tests (no tests exist yet; create under `test/`)
- `flutter analyze` — static analysis (uses `flutter_lints` v6 from `analysis_options.yaml`)
- `dart format .` — format code

## Platform targets
android, ios, linux, macos, web, windows (standard Flutter multi-platform app).

## Entrypoint
`lib/main.dart` — single entrypoint, currently a default Hello World app.

## Dart SDK
`^3.12.0` — Dart 3 patterns, records, and other 3.x features available.

## Agent skills
20 pre-installed skills in `.agents/skills/` covering Flutter, Dart, Firebase, animations, testing, responsive layout, accessibility, SEO, bash, and caveman modes. Auto-trigger for matching tasks.
