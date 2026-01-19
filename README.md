# CommonGrounds MDA

CommonGrounds is a Flutter-based student task and study management app designed to help students stay organized, manage assignments, plan study sessions, and improve productivity.

## 🚀 Getting Started

This guide will help you set up the project on your local machine for development and testing.

### Prerequisites

Before you begin, ensure you have the following installed:

1.  **Flutter SDK**: [Install Flutter](https://docs.flutter.dev/get-started/install) for your operating system.
2.  **Git**: [Install Git](https://git-scm.com/downloads).
3.  **IDE**: Recommended: [Visual Studio Code](https://code.visualstudio.com/) (with Flutter extension) or [Android Studio](https://developer.android.com/studio).

### 📥 Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Rcabugnason025/Common-Grounds-MDA.git
    cd Common-Grounds-MDA
    ```

2.  **Install dependencies**:
    ```bash
    flutter pub get
    ```

3.  **Verify installation**:
    Run the following command to check for any missing requirements:
    ```bash
    flutter doctor
    ```

### 📱 Running the App

You can run the app on an Android emulator, physical device, web browser, or Windows desktop.

**Run on any connected device:**
```bash
flutter run
```

**Run specifically on Chrome (Web):**
```bash
flutter run -d chrome
```

**Run on Windows Desktop:**
```bash
flutter run -d windows
```

### 🧪 Running Tests

To verify that the application code is working correctly:

```bash
flutter test
```

### 📂 Project Structure

-   `lib/main.dart`: The entry point of the application.
-   `lib/pages/`: Contains the application screens (e.g., `splash_screen.dart`).
-   `lib/theme/`: Contains app styling and theme definitions (`app_theme.dart`).
-   `lib/model/`: Data models for the application.
-   `lib/data/`: Mock data used for development.

### 🛠 Troubleshooting

-   **Dependencies issues**: If you encounter errors related to packages, try cleaning the build cache:
    ```bash
    flutter clean
    flutter pub get
    ```
-   **Device not found**: Ensure your emulator is running or your physical device is connected with USB debugging enabled. Check connected devices with:
    ```bash
    flutter devices
    ```
