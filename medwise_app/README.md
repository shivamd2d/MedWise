# MedWise - Smart Pill Reminder App

## Overview
MedWise is a smart pill reminder application designed to help users manage their medication schedules effectively. The app provides features such as medication tracking, reminders, caregiver notifications, and pill detection using machine learning.

## Features
- **Medication Management**: Add, edit, and track medications with dosage and schedule.
- **Reminders**: Receive push notifications and voice reminders for medication intake.
- **Caregiver Support**: Manage caregiver contacts and send alerts for missed doses.
- **Pill Detection**: Use the camera to verify pills with machine learning integration.
- **Progress Tracking**: Monitor medication adherence with visual charts and history logs.
- **Multi-language Support**: Available in multiple languages for broader accessibility.

## Project Structure
The project is organized into several directories for better maintainability:

```
lib/
├── core/                  # Core functionalities and utilities
│   ├── constants/         # App-wide constants
│   ├── theme/             # Theme definitions
│   └── utils/             # Utility functions
├── data/                  # Data models, repositories, and services
│   ├── models/            # Data models
│   ├── repositories/      # Data access layers
│   └── services/          # Services for database, notifications, etc.
├── presentation/          # UI components and state management
│   ├── providers/         # State management providers
│   ├── screens/           # Screen layouts
│   └── widgets/           # Reusable widgets
└── l10n/                  # Localization files
```

## Getting Started

### Prerequisites
- Flutter SDK installed on your machine.
- An IDE such as Android Studio or Visual Studio Code.

### Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd medwise_app
   ```
3. Install dependencies:
   ```
   flutter pub get
   ```

### Running the App
To run the app on an emulator or physical device, use:
```
flutter run
```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.