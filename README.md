# Android Offline Web App

This project is an Android application designed to load and display the website `xn--b1adrrjq1b5c.online` offline. The application fetches the website content and stores it in a local database, allowing users to access the site without an internet connection.

## Features

- Offline access to the website content
- User-friendly interface
- Efficient data storage and retrieval

## Project Structure

- **app/src/main/java/com/example/MainActivity.java**: Main entry point of the application, handling website loading and database interactions.
- **app/src/main/res/layout/activity_main.xml**: Layout file defining the user interface components.
- **app/src/main/res/values/strings.xml**: Contains string resources used throughout the application.
- **app/src/main/AndroidManifest.xml**: Manifest file declaring application components and permissions.
- **build.gradle**: Gradle build configuration file specifying dependencies and build settings.
- **settings.gradle**: Configuration file for the Gradle build system.

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Open the project in your preferred IDE.

3. Build the project to download the necessary dependencies.

4. Run the application on an Android device or emulator.

## Usage

Upon launching the app, it will automatically fetch the website content and store it in the local database. Users can navigate the site offline without needing an internet connection.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.