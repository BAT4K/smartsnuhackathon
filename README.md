# जननी (Janani) - Women's Safety Web App

जननी (Janani) is a web application designed to enhance women's safety by providing critical features such as live location tracking, SOS alerts, and emergency contacts. This app is aimed at helping individuals in distress by offering quick access to safety measures, including siren alerts, nearby devices detection, and identifying the safest route to safety.

## Features

### 1. Login/Signup Page
- Allows users to create an account or log in using a simple form.
- User credentials are stored in the browser's LocalStorage.
- On successful login, users are redirected to the home page.

### 2. Home Page
The home page serves as the central hub for safety features, offering:

- *Live Location Map*: Displays the user's current location on an interactive map.
- *Emergency Contacts*: A button to quickly access emergency contacts and call them.
- *Live Location Sharing*: Share your live location with designated contacts.
- *SOS Button*: Instantly sends an SOS alert with your current location to your emergency contacts.
- *Nearby Devices*: Detect nearby devices for potential help or support.
- *Siren Activation*: Activates a loud siren to attract attention during emergencies.
- *Safest Route*: Suggests the safest route to reach your destination.
- *Hamburger Menu*: Provides access to a logout button for secure session termination.

### 3. Logout Functionality
- The hamburger menu includes a "Log Out" button to allow users to securely log out of the app.

## Technologies Used
- *HTML5, CSS3, JavaScript*: Core web technologies for the app interface and functionality.
- *LocalStorage*: Stores user login/signup data locally for easy access.
- *Map API*: Displays the live location of the user on a map.

## How to Run Locally

1. Clone the repository:

    ```bash
    git clone https://github.com/BAT4K/smartsnuhackathon.git
    cd smartsnuhackathon/janani
    

2. Open the index.html file in your preferred browser to launch the app.

> *Note*: Ensure you have an active internet connection to enable live location tracking features.

## Future Enhancements

- *Real-time Database Integration*: Replace LocalStorage with a more secure and scalable backend database.
- *Push Notifications*: Implement notifications to alert users or contacts in real-time during emergencies.
- *Improved Security*: Implement features like OTP verification for added security during user login/signup.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
