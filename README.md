#smartsnuhackathon

## Overview

The Women Safety App provides users with essential features for personal safety, including emergency contact management, live location sharing, and an SOS button. This app aims to enhance personal safety by providing quick access to emergency services and important contacts.

## Features

- **Login / Signup**: Users can create an account or log in to access the app's features.
- **Emergency Contacts**: Store and manage emergency contact numbers.
- **Live Location**: Share your real-time location with emergency contacts.
- **SOS Button**: Quickly trigger an SOS alert and call emergency services.

## Getting Started

To get started with the Women Safety App, follow these steps:

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/women-safety-app.git
    ```

2. **Navigate to the Project Directory**

    ```bash
    cd women-safety-app
    ```

3. **Open the HTML Files**

    Open `index.html` in your web browser to access the login/signup page. The `index.html` file includes the login and signup forms.

4. **View the Women Safety Features**

    After logging in, you can access the Women Safety features by navigating to the appropriate section. The following features are available:
    
    - **Emergency Contacts**: Navigate to `index.html` to manage your emergency contacts.
    - **Live Location**: Navigate to `maps.html` to view your live location.
    - **SOS Button**: Navigate to `sos.html` to trigger an SOS alert.

## File Structure

- `index.html`: Login and Signup forms.
- `maps.html`: Live Location page.
- `sos.html`: SOS Button page.
- `background.jpg`: Background image used in the app.

## Style Consistency

The app uses the `Poppins` font for a consistent look and feel. The primary color scheme is centered around shades of blue for main buttons, with distinctive colors for different actions:

- **Primary Button**: `#0078D4`
- **Hover Color**: `#005A9E`
- **Live Location Button**: `#FF5722`
- **SOS Button**: `#d9534f`

## JavaScript Functions

- **`login()`**: Handles user login and checks credentials against local storage.
- **`signup()`**: Registers a new user and stores credentials in local storage.
- **`showSignup()`**: Switches the view to the signup form.
- **`showLogin()`**: Switches the view to the login form.
- **`showWomenSafety()`**: Displays the Women Safety section after successful login.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please submit a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
