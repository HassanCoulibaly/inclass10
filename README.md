Signup Page - Flutter Form Validation Demo
Overview
This is a Flutter application developed as part of In Class Activity 10: Flutter Form Input Validation - Building a Signup Page. The project creates a signup page with form fields for user input, including date of birth (with a date picker), email, first name, last name, phone number, and age. It implements form validation and provides feedback upon submission. This is a collaborative effort between Venkata Saileenath Reddy Jamapala and Hassan Coulibaly.

Due Date: March 24, 2025, 8:30 PM
Objective: Build a functional signup page in Flutter with form validation and navigation.
Features
Form Fields:
Date of Birth (with a calendar picker)
Email
First Name
Last Name
Phone Number
Age
Validation: Ensures all fields are filled before submission.
User Interface: Clean, scrollable form with a bold "SIGN UP FORM" header.
Feedback: Displays a "Processing Data" snackbar on successful submission.
Prerequisites
Flutter SDK: Version 2.12.0 or higher (tested with 3.7.0)
Dart SDK: Included with Flutter (3.7.0 recommended)
IDE: Visual Studio Code, Android Studio, or any Flutter-supported editor
Git: For version control and GitHub collaboration
Setup Instructions
Clone the Repository:
bash

Collapse

Wrap

Copy
git clone <repository-url>
cd signuppage
Install Dependencies:
Ensure your pubspec.yaml matches the one below, then run:
bash

Collapse

Wrap

Copy
flutter pub get
Run the App:
Connect a device or start an emulator/simulator, then:
bash

Collapse

Wrap

Copy
flutter run
Project Structure
lib/main.dart: Contains the main application code, including the signup form and validation logic.
pubspec.yaml: Defines project dependencies and SDK constraints.
pubspec.yaml
yaml

Collapse

Wrap

Copy
name: signuppage
description: "A new Flutter project."
publish_to: 'none'

version: 1.0.0+1

environment:
  sdk: '>=2.12.0 <4.0.0'

dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.2

dev_dependencies:
  flutter_test:
    sdk: flutter
  flutter_lints: ^2.0.0

flutter:
  uses-material-design: true
Usage
Launch the app to see the "Form Validation Demo" screen.
Fill out the form:
Tap the "Date of Birth" field to select a date from the calendar.
Enter text in the other fields (email, first name, last name, phone number, age).
Press "Submit":
If all fields are valid, a "Processing Data" snackbar appears.
If any field is empty, validation errors will display below the respective fields.
Screenshots
(Add screenshots here if required by your instructor. You can capture these by running the app and using a screenshot tool.)

Submission Details
Group Members: Venkata Saileenath Reddy Jamapala, Hassan Coulibaly
GitHub Repository: [Insert GitHub URL here]
Main File: lib/main.dart
Instructions:
Both group members collaborated via GitHub, with commit history reflecting contributions.
Submit the main.dart file and the GitHub repository link to the assignment portal by 8:30 PM on March 24, 2025.
Notes
The project meets the core requirements of the activity: form creation, input validation, and UI design.
Navigation to a confirmation screen is not implemented in this version but can be added by extending the ElevatedButton’s onPressed logic with Navigator.push.
The date picker fulfills the "explore the calendar widget" hint from the activity.
Troubleshooting
Dependencies Fail: Run flutter clean followed by flutter pub get.
SDK Version Issues: Ensure your Flutter SDK is 2.12.0 or higher (flutter --version to check; flutter upgrade to update if needed).
Form Not Scrolling: The ListView ensures scrollability; test on smaller screens to confirm.
Future Improvements
Add navigation to a confirmation page after submission.
Enhance validation (e.g., email format, phone number regex).
Style the UI with custom themes or colors.
