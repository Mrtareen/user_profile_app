# User Profile App 🚀

## Overview
This Flutter app fetches user data from an API and displays it, including **name, email, and profile picture**.

## Features
- Fetches data using the `http` package.
- Parses JSON response into a Dart model (`User`).
- Displays user details in a responsive UI.
- Uses `FutureBuilder` for API calls.

## Installation
1. Install Flutter from [flutter.dev](https://flutter.dev).
2. Clone the repository:
git clone https://github.com/your-repo/user-profile-app.git cd user-profile-app

## Project Structure
user_profile_app/ │── lib/ │ ├── main.dart │ ├── api_service.dart │ ├── user.dart │── android/app/src/main/AndroidManifest.xml │── pubspec.yaml │── README.md

## API Details
- The app fetches user details from:
https://api.example.com/user-profile

- Example JSON response:
```json
{
  "name": "John Doe",
  "email": "johndoe@example.com",
  "profilePicture": "https://example.com/profile.jpg"
}

This project is open-source under the MIT License.
