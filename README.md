# UserLoginApp - iOS SwiftUI

A simple user login and signup app built using **SwiftUI** and **AppStorage** for local data persistence. The application provides two main features:
- User Sign Up: Store credentials locally.
- User Login: Verify credentials against stored data.

## Features

- SwiftUI-based UI
- Secure password fields
- Credential validation
- Simple navigation using `NavigationView`
- Use of `@AppStorage` for persistent storage
- Alert handling for errors and invalid logins

## Screens

### Login Screen
- Username & password input
- Validates credentials with saved ones
- Navigates to a dummy login success screen or shows an error

### Sign Up Screen
- Accepts username, password, and confirm password
- Checks password match
- Stores credentials locally
- Includes clear/reset inputs functionality

## Code Files

### `ContentView.swift`
- Main login interface
- Handles navigation to Sign Up and Login success views
- Validates input fields using stored values

### `SignUpScreen.swift`
- Takes new user input
- Saves to `@AppStorage`
- Basic validation (password match)
- Option to go back to login and reset input

### `UserLoginAppApp.swift`
- App entry point
- Loads `ContentView` on launch

## Requirements

- iOS 14.0+
- Xcode 12.0+
- Swift 5.3+

## Getting Started

1. Clone the repository
2. Open in Xcode
3. Run on Simulator or a physical iOS device

## Author

- **Mansi K**

