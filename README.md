# Flutter Login & Registration App

A clean, responsive, and modern Flutter application featuring fully functional Login and Registration interfaces built with Material 3.

## Short Description

This project demonstrates core Flutter UI development concepts, including state management, input handling, custom form validation (email formatting, password matching, and length checks), password visibility toggles, keyboard-friendly scrolling, and screen navigation between authentication flows.

---

## Features

### 🔑 Login Screen
- **User Inputs:** Email/Username and Password text fields.
- **Password Visibility:** Toggle button to show or hide the password.
- **Validation:** Instant feedback for empty or invalid inputs.
- **Action Options:** "Forgot Password?" action with interactive feedback.
- **Navigation:** Direct link to navigate to the Registration screen.

### 📝 Registration Screen
- **User Inputs:** Full Name, Email, Password, and Confirm Password text fields.
- **Validation:**
    - Email regex verification (`name@example.com`).
    - Minimum password length checks (6+ characters).
    - Password matching validation (`Password` vs `Confirm Password`).
- **Navigation:** Top bar back button and bottom link to navigate back to the Login screen.

---

## Screenshots

| Login Page | Registration Page |
| :---: | :---: |
| ![Login Page](screenshots/login.png) | ![Registration Page](screenshots/register.png) |

> **Note:** Add your actual app screenshots to a folder named `screenshots` in your repository root with filenames `login.png` and `register.png`.

---

## Technologies Used

- **Framework:** [Flutter](https://flutter.dev/) (v3.x)
- **Language:** [Dart](https://dart.dev/) (v3.x)
- **Design System:** Material Design 3

---

## Project Structure

```text
loginpagee/
├── android/
├── ios/
├── lib/
│   ├── main.dart           # App entry point & theme configuration
│   ├── login_page.dart     # Login screen UI & logic
│   └── register_page.dart  # Registration screen UI & validation
├── screenshots/            # App screenshots for documentation
│   ├── login.png
│   └── register.png
├── pubspec.yaml            # Project dependencies & assets configuration
└── README.md               # Project documentation