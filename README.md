# Women Safety App

## Overview

The Women Safety App is designed to provide safety features for women, including emergency contact access, live location sharing, SOS alerts, device proximity detection, siren activation, and safe route guidance. The application consists of two primary pages:

1. **Login Page** (`login.html`)
2. **Women Safety Page** (`women_safety.html`)

## Features

### 1. Login Page (`login.html`)

**Purpose**: Allows users to log in or sign up for the Women Safety App.

**Features**:
- **Login Form**: Users can log in using their username and password.
- **Signup Form**: New users can create an account.
- **Local Storage**: User credentials are stored in `localStorage` for authentication.
- **Redirection**: Upon successful login, users are redirected to the Women Safety Page.

**Usage**:
- **Login**: Enter a registered username and password, then click "Login".
- **Sign Up**: Click on "Create an account" to switch to the signup form, enter details, and click "Sign Up". After successful signup, you will be redirected to the login form.

**Code**: 
- [login.html](login.html)

### 2. Women Safety Page (`women_safety.html`)

**Purpose**: Provides safety features and information to logged-in users.

**Features**:
- **Welcome Message**: Personalized greeting using the logged-in username.
- **Map Integration**: Displays the user's current location on a map.
- **Buttons**: Access various features:
  - **Emergency Contacts**: Link to emergency contact management.
  - **Live Location**: Share your live location.
  - **SOS**: Trigger an SOS alert.
  - **Devices Nearby**: Detect nearby devices.
  - **Siren**: Activate a siren.
  - **Safest Route**: Find and display the safest route.

**Usage**:
- **Menu**: Use the hamburger menu to navigate between features and log out.
- **Map**: The map shows your current location. It uses Leaflet for map rendering and updates.

**Code**: 
- [women_safety.html](women_safety.html)

## Setup

1. **Ensure you have the following files in your project directory**:
   - `login.html`
   - `women_safety.html`
   - Any required background images or external CSS/JS files.

2. **Local Storage**: The application uses `localStorage` to manage user authentication. Make sure your browser supports and has `localStorage` enabled.

3. **Dependencies**:
   - **Leaflet**: Used for map functionality in `women_safety.html`. The library is included via CDN.

4. **Testing**:
   - Open `login.html` in your browser to test the login and signup functionality.
   - After logging in, `women_safety.html` should display and provide the features as described.

## Development

- **HTML/CSS**: Modify `login.html` and `women_safety.html` for design changes.
- **JavaScript**: Update `login.html` for authentication logic and `women_safety.html` for map integration and feature buttons.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
