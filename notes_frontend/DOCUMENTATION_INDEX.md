# Documentation Index

This app stores notes locally on-device and does not require any backend or external services. The full documentation set is provided under kavia-docs at the repository root.

Primary documents
- kavia-docs/README.md — Project overview, features, getting started, running preview, build, folder structure, style guide notes, troubleshooting
- kavia-docs/ARCHITECTURE.md — High-level architecture for the Flutter app with local storage, components, navigation, and state management (Provider)
- kavia-docs/CONTRIBUTING.md — Coding standards, commit message convention, branching, code review process
- kavia-docs/CODE_QUALITY.md — Linting, formatting, and static analysis guidance
- kavia-docs/TROUBLESHOOTING.md — Common issues and their resolution steps
- kavia-docs/TESTING.md — How to run tests locally and resolve current analyzer issues
- kavia-docs/DEVELOPER_NOTES.md — Notes on expected app entry (lib/main.dart and MyApp) referenced by tests

Quick start
- cd simple-notes-app-*/notes_frontend
- flutter pub get
- flutter run

Known analyzer status
- The widget test refers to package:notes_frontend/main.dart and MyApp. If these are not yet implemented, analyzer and tests will fail until lib/main.dart and MyApp exist or the test is adjusted as described in the docs.
