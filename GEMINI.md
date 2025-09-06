# GEMINI Project Analysis: device_calendar

## Project Overview

This project is a Flutter plugin named `device_calendar`. Its purpose is to provide a cross-platform API for interacting with the device's native calendar functionalities. The plugin allows developers to request permissions, retrieve calendars and events, and perform create, read, update, and delete (CRUD) operations on calendar events. It supports Android, iOS, and macOS platforms.

The core logic is written in Dart, with platform-specific implementations in Kotlin for Android and Swift for iOS and macOS. The project includes an example application that demonstrates the plugin's features.

## Building and Running

### Prerequisites

- Flutter SDK
- Android SDK (for Android development)
- Xcode (for iOS and macOS development)

### Running the Example App

1.  Navigate to the `example` directory:
    ```bash
    cd example
    ```
2.  Install dependencies:
    ```bash
    flutter pub get
    ```
3.  Run the app:
    ```bash
    flutter run
    ```

### Running Tests

To run the unit tests for the plugin, execute the following command from the root directory:

```bash
flutter test
```

The project also contains integration tests within the `example/integration_test` directory.

## Development Conventions

- **Code Style:** The project follows the standard Dart and Flutter coding conventions, enforced by the `flutter_lints` package, as specified in the `analysis_options.yaml` file.
- **Versioning:** The `CHANGELOG.md` file is maintained with a detailed history of changes for each version, following the "Keep a Changelog" format.
- **Continuous Integration:** The project uses GitHub Actions for continuous integration. The workflow, defined in `.github/workflows/dart.yml`, includes jobs for running tests, performing a dry-run of publishing the package, and building the example app for Android and iOS.
cific linting rules are defined in the `analysis_options.yaml` file.
*   **Versioning:** The project uses semantic versioning. The version number is updated in the `pubspec.yaml` file.
*   **Changelog:** All changes are documented in the `CHANGELOG.md` file.
*   **Branching:** The project appears to use a Gitflow-like branching model, with `develop`, `release`, `hotfix`, and `master` branches.
*   **Continuous Integration:** The project uses GitHub Actions for continuous integration. The CI pipeline is defined in the `.github/workflows/dart.yml` file. The pipeline runs tests and builds the example app for Android and iOS.
