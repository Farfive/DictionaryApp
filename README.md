# Clean Architecture Dictionary App

This project is an Android application built with Kotlin that implements a dictionary app using the MVVM (Model-View-ViewModel) architecture. It utilizes various technologies such as API integration, Room database, Jetpack Compose, and Kotlin.

## Features

- Search for word definitions and meanings.
- Save favorite words for quick access.
- Offline mode with locally stored definitions.
- User-friendly UI with Jetpack Compose.

## Technologies Used

- Android SDK
- Kotlin
- MVVM architecture
- API integration
- Room database
- Jetpack Compose

## Setup and Installation

To set up the project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/dictionary-app.git`
2. Open the project in Android Studio.
3. Build and run the application on an Android device or emulator.

Note: Make sure you have the latest version of Android Studio and the Android SDK installed.

## Project Structure

The project follows a clean architecture pattern to ensure separation of concerns and maintainability. Here's an overview of the main modules:

- `app`: Contains the main Android application module, including the UI components and entry point.
- `data`: Handles data retrieval and management, including API integration and local database operations.
- `domain`: Defines the business logic and entities of the application.
- `presentation`: Implements the MVVM pattern, handling the presentation layer and UI logic using Jetpack Compose.

## Contributions

Contributions to this project are welcome. If you find any bugs or have ideas for new features, please open an issue or submit a pull request with your changes.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as per the terms of the license.

## Acknowledgements

This project utilizes various open-source libraries and technologies, including Jetpack Compose, Retrofit, Room, and others. Special thanks to their developers for their contributions.

## Contact

If you have any questions or suggestions, feel free to reach out to the project maintainer via email at `laszanowskin@gmail.com`.

Happy coding!
