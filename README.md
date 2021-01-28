# Clicksend Mobile Flutter


# Installation
- This assumes you are using Android Studio as the IDE
  - Clone the Project: ```https://github.com/basilmariano/clicksend_flutter.git```
  - Open Android Studio > Open Exising Android Studio Project
  - Select the folder created from the git clone
  - run ```flutter pub get``` or Go to Tools > Flutter > click the ```Get Flutter Packages Get```
  - run the on the emulator or Android Device
  

# Achitechture
- Provider is basically ScopedModel which is the most practical and straight forward approach to build apps in Flutter.

# Unit Testing
- Open your favorite terminal
  - go to project root directory
  - run ```flutter test```
  - to test specific file ```flutter test test/{directory}/{view_model}_test.dart```
# Integration Testing
- Open your favorite terminal
  - go to project root directory
  - to test specific file ```flutter drive --target=test_driver/{filename}.dart```
