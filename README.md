# StudentOS

<img width="1920" height="797" alt="Mobile App presentation" src="https://github.com/user-attachments/assets/07a559f6-3fe0-4591-8a23-9a128c0bfa7f" />



[![Android](https://img.shields.io/badge/Platform-Android-green.svg)](https://developer.android.com)
[![Kotlin](https://img.shields.io/badge/Kotlin-2.0-blue.svg)](https://kotlinlang.org)
[![Compose](https://img.shields.io/badge/Jetpack-Compose-7F5AF0.svg)](https://developer.android.com/jetpack/compose)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Build](https://img.shields.io/badge/CI-GitHub%20Actions-success.svg)](.github/workflows/android-ci.yml)

A modern Android student productivity app designed to help students keep track of courses, assignments, focus sessions, and academic progress in one clean interface.

## Why StudentOS

StudentOS combines a polished dashboard, task organization, and study-session support to give students a simple command center for their academic routine.

### Highlights

- Clean Material 3 interface
- Smart dashboard with weekly progress and study streak
- Course and assignment tracking
- Focus session flow for study blocks
- Local persistence with Firebase-ready integration

## Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/fc8e396d-61da-4c6d-a6df-c488189b44b7" width="180" alt="Dashboard" />
  <img src="https://github.com/user-attachments/assets/0cde44a8-5b91-4e95-afc3-8db512fe84f4" width="180" alt="Courses" />
  <img src="https://github.com/user-attachments/assets/97ff805e-d16f-4572-9bad-b7c5aa870aea" width="180" alt="Assignments" />
  <img src="https://github.com/user-attachments/assets/6f244b34-9039-479f-acbe-caa2e1b47b6a" width="180" alt="Profile" />
</p>

A quick look at the StudentOS experience: dashboard, courses, assignments, and profile screens.

## Tech Stack

- Kotlin
- Jetpack Compose
- Material 3
- Navigation Compose
- Room Database
- Firebase Auth / Firestore
- ViewModel + StateFlow

## Getting Started

### Prerequisites

- Android Studio
- JDK 11 or newer
- Android SDK with API 35

### Run the app

1. Open the project in Android Studio.
2. Sync Gradle.
3. Launch an emulator or connect a device.
4. Run the app.

### Build

```bash
./gradlew assembleDebug
```

## Project Structure

```text
app/
  src/main/java/com/studentos/app/
    ui/           # Screens and Compose UI
    navigation/   # Route definitions
    viewmodel/    # Screen state and logic
    data/         # Repositories, Room, Firebase integration
```

## Roadmap

- Improve analytics and reporting
- Add reminders and notifications
- Expand study-session insights
- Polish the onboarding experience

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
