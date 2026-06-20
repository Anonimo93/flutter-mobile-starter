# Flutter Mobile Starter

> Cross-platform mobile application starter built with Flutter and Kotlin.

## Stack

| Layer | Technology |
|-------|-----------|
| **Framework** | Flutter · Dart |
| **Native** | Kotlin (Android) |
| **Architecture** | MVVM · Clean Architecture |
| **State Mgmt** | Riverpod / Bloc |
| **Networking** | Dio · REST APIs |
| **Local DB** | Hive · SQLite |
| **Auth** | OAuth2 · JWT |

## Features

- Cross-platform (Android + iOS) from a single codebase
- MVVM architecture for testability
- Reactive state management with Riverpod
- REST API integration with Dio
- Local persistence with Hive
- Dark/light theme support
- Responsive UI following Material 3 guidelines
- Push notifications (Firebase)

## Getting Started

```bash
git clone https://github.com/Anonimo93/flutter-mobile-starter.git
cd flutter-mobile-starter
flutter pub get
flutter run
```

## Project Structure

```
lib/
├── core/          # Theme, constants, network
├── models/        # Data models
├── providers/     # State management
├── repositories/  # Data layer
├── screens/       # UI screens
├── widgets/       # Reusable components
└── main.dart
```

## Requirements

- Flutter SDK >= 3.x
- Dart >= 3.x
- Android Studio / Xcode for builds

## Roadmap

- [ ] Add offline-first sync
- [ ] Add CI/CD with Codemagic
- [ ] Add unit & widget tests

---

*Built with Flutter — one codebase, two platforms.*
