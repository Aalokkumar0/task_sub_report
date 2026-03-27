# task_sub_report# 📱 Flutter Installation Task
##Objective
Set up a complete Flutter development environment and run a sample Flutter application successfully on an emulator or a physical device.
## ⚙️ Setup Process
### 1. Install Flutter SDK
* Download Flutter SDK from the official website
* Extract it to a desired location (e.g., `C:\flutter`)
* Add Flutter to system PATH:
  C:\flutter\bin
### 2. Install IDE
Installed:
* Visual Studio Code (VS Code)
### 3. Install Required Plugins
* Flutter
* Dart
### 4. Device Setup
#### Option A: Android Emulator
* Created using Android Studio (AVD Manager)
#### Option B: Physical Device
* Enabled Developer Options
* Enabled USB Debugging
---

### 5. Verify Installation bash
flutter doctor

 Output:

![Flutter Doctor Output](screenshots/flutter_doctor.png)

##  Project Creation
```bash
flutter create demo_app
cd demo_app
flutter run
```

---

##  Output
* Default Flutter app ran successfully
* Verified on emulator/devic
---
##  Custom Changes

```dart
AppBar(
  title: Text("My First Flutter App"),
)
```

---

## Screenshots

### Flutter Doctor Result
![Flutter Doctor](screenshots/flutter_doctor.png)
## 📁 Project Structure
demo_app/
│── lib/
│   └── main.dart
│── android/
│── ios/
│── pubspec.yaml


## Conclusion

Flutter SDK installed successfully and verified using `flutter doctor`.
Project created and executed without critical errors.

---

## Author

**Aalok Kumar**
