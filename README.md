# Moodle UI Android App

This repository contains an Android application project (`com.example.moodleui`) aimed at building a user interface for Moodle. 

## 📱 About the Project

The app is built natively for Android using Java. It utilizes a modern Android development stack and includes features such as user authentication and network requests to communicate with a Moodle backend (or similar services).

**Key Technologies:**
- **Language**: Java
- **Minimum SDK**: 29 (Android 10)
- **Target SDK**: 34 (Android 14)
- **Networking**: Volley (`com.android.volley:volley:1.2.1`)
- **UI Components**: Material Design Components (`com.google.android.material`), AppCompat, ConstraintLayout.

## 📂 Project Structure

- `app/`: The main Android application module containing all the source code and resources.
  - `src/main/java/`: Java source code for the app logic.
  - `src/main/res/`: Android resources including layouts, strings, and drawables.
  - `build.gradle.kts`: Gradle build script for the app module.
- `user_auth/`: A module or directory dedicated to user authentication flows (login, registration, etc.).
- `Slide/`: Contains presentation slides related to the project development or final showcase.
- `gradle/`: Gradle wrapper files to ensure consistent build environments.

## 🚀 Getting Started

To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MynameisHoangAnh/MoodleUi_Project.git
   ```
2. **Open the project in Android Studio**:
   - Launch Android Studio.
   - Select **Open** and navigate to the cloned `MoodleUi_Project` directory.
3. **Sync Project with Gradle Files**: Wait for Android Studio to download dependencies and sync the project.
4. **Run the App**: Connect an Android device (API 29+) or start an Emulator, then click the **Run** button (Shift + F10) to install and launch the app.

## 🌐 Network Configuration
The application uses Volley for network requests. Ensure that any backend URLs used for API calls are reachable from your device or emulator. If testing locally, you might need to configure network security configs or use appropriate IP addresses (e.g., `10.0.2.2` for localhost on the Android Emulator).
