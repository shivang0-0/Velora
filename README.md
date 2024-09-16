# Velora
___
Velora is a React Native application built with TypeScript, designed to provide a scalable and maintainable codebase. This README outlines the directory structure of the project and guides you on where to place various parts of your code.

## Project Structure
___
The project is organized into the following main directories within the `src` folder:

```plaintext
Velora/
│
├── android/                # Native Android project files (auto-generated)
│
├── ios/                    # Native iOS project files (auto-generated)
│
├── src/                    # Main source directory for the app
│   ├── api/                # API calls and service layer
│   ├── assets/             # Static assets like images, fonts, etc.
│   ├── components/         # Reusable UI components
│   ├── hooks/              # Custom hooks for reusable logic
│   ├── navigation/         # Navigation configuration and screens
│   ├── screens/            # Screen components (organized by feature or section)
│   ├── store/              # State management (e.g., Redux, Zustand)
│   ├── styles/             # Global styles and theme configurations
│   └── utils/              # Utility functions and helpers
│
├── App.tsx                 # Main App component entry point
└── index.tsx               # Entry file for the app
```

## Getting Started
___

### Install Dependencies:

```
npm install
```
### Start Metro Server:
To start the Metro bundler, run:
```
npx react-native start
```

### Run on Android:
To run the app on an Android emulator or connected device:
- Make sure you have an Android emulator running or a physical device connected.
- Open a new terminal window.
- Run the following command: ```npx react-native run-android```.

### Run on iOS:
To run the app on an iOS simulator or connected device:
- Make sure you have Xcode installed (for iOS simulator).
- Open a new terminal window.
- Run the following command: ```npx react-native run-ios```.

## Development
___
Follow the project structure outlined above when adding new features or components. Keep the codebase organized and maintainable by adhering to the established architecture.


## Contributing
___
To contribute to the Velora project:

1. Clone the project to your local machine.
2. Create a new branch for each feature you're working on. Use the naming convention `feature-<feature-name>` (e.g., `feature-user-authentication`).
3. Make your changes and commit them to your feature branch.
4. When your feature is complete, raise a Pull Request (PR) to merge your changes into the `main` branch.
5. Wait for code review and address any feedback.

Note: A separate `release` branch will be maintained from the `main` branch for managing releases. Do not directly commit to the `release` branch unless instructed to do so by the project maintainers.