# Ricafort - Student Profile Form (Act 05)

A simple Flutter app demonstrating form handling and state management.

## Fields
- Full Name
- Age
- Gender (dropdown)
- Address
- Contact Number
- Email

## Features
- Required-field validation on every input
- Age must be a number between 1 and 100
- Contact number must be 10-11 digits
- Email must match a basic email pattern
- **Submit** validates the form and displays the entered info in a card below
- **Clear / Reset** empties all fields and removes the displayed summary

## How to run
This folder only contains the Dart source (`lib/main.dart`) and `pubspec.yaml`.
To run it in VS Code:

1. Make sure the Flutter SDK is installed (`flutter --version` to check).
2. Create a new Flutter project shell (only needed once), or place these two
   files into an existing Flutter project:
   ```
   flutter create ricafort_act05
   ```
3. Copy `lib/main.dart` and `pubspec.yaml` from this folder into the new
   project, overwriting the generated ones.
4. Get packages and run:
   ```
   cd ricafort_act05
   flutter pub get
   flutter run
   ```
   (Choose Chrome, an emulator, or a connected device when prompted.)

## Author
Franz Andrei T. Ricafort
