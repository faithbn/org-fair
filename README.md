# CICT Org Fair

**Live app:** https://faithbn.github.io/org-fair/

CICT Org Fair lets students browse organizations, view fair events, and check event updates from the CMS.

## Run locally

Copy `cms.example.json` to `cms.json`, fill in the Contentful values, then run:

```powershell
flutter run --dart-define-from-file=cms.json
```

`cms.json`, Android signing properties, and keystores are ignored by Git. Use a read-only Contentful token.

## Build for the web

```powershell
flutter build web --release --dart-define-from-file=cms.json
```

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
