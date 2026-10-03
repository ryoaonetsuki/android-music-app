# iMusic Android

An Android music application with a native mobile interface.

## Overview

This repository contains the Android source code, resources, and build configuration for the application.

## Requirements

- Android Studio
- Android SDK
- JDK version supported by the project's Gradle configuration

## Setup

1. Clone the repository.
2. Open the project in Android Studio.
3. Allow Gradle to sync and download dependencies.
4. Connect an Android device or start an emulator.
5. Run the **app** configuration.

You can also build from the project root with the included Gradle wrapper:

```bash
./gradlew assembleDebug
```

On Windows:

```bat
gradlew.bat assembleDebug
```

## Project Structure

- `app/` — Android application module
- Gradle files — build and dependency configuration
- Android resources — layouts, strings, images, and other app resources

## Development

Make changes inside the Android project, sync Gradle when dependencies change, then build and test on an emulator or physical device.

## Notes

Do not commit local SDK paths, signing keys, passwords, or other secrets.
