
# NATIVE FEATURES UDEMY ASSIGNMENT  🚀 💻



# Overview
This project demonstrates the integration and usage of native device features within a mobile application built using React Native. Created as part of a Udemy assignment, it showcases how to leverage device capabilities like the camera, location, file system, and more to create a feature-rich application.

# Features
- Camera Integration: Capture photos using the device's camera.
- Location Access: Retrieve and display the user’s current location.
- File System Access: Save and retrieve files from the device's storage.
- Custom Models: Utilize structured data models for better app architecture.
- Responsive Screens: Ensure seamless functionality across devices.



 

##  Screenshots
![App Screenshot](./screenshots/overview.png)

## Packages Used
This project uses the following packages to integrate native features and manage dependencies:

- react: Core React library for building user interfaces.
- react-native: React Native library for cross-platform mobile app development.
- expo: Provides a set of tools and APIs for easier development.
- expo-camera: Enables access to the device camera for capturing photos or videos.
- expo-location: Provides geolocation services to fetch the user’s location.
- expo-file-system: Allows reading and writing to the device’s file system.
- expo-permissions: Manages runtime permissions required for accessing native features.
- react-navigation/native: Manages navigation between screens.
- react-native-gesture-handler: Enables smooth touch interactions and gesture-based navigation.
- react-native-screens: Optimizes screen transitions for better performance.
- react-native-safe-area-context: Ensures proper UI layout in areas like notches and rounded corners.
- react-native-reanimated: Provides high-performance animations for a smooth user experience.


# Getting Started

>**Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions till "Creating a new application" step, before proceeding.

## Step 1: Start the Metro Server

First, you will need to start **Metro**, the JavaScript _bundler_ that ships _with_ React Native.

To start Metro, run the following command from the _root_ of your React Native project:

```bash
# using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Start your Application

Let Metro Bundler run in its _own_ terminal. Open a _new_ terminal from the _root_ of your React Native project. Run the following command to start your _Android_ or _iOS_ app:

### For Android

```bash
# using npm
npm run android

# OR using Yarn
yarn android
```

### For iOS

```bash
# using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up _correctly_, you should see your new app running in your _Android Emulator_ or _iOS Simulator_ shortly provided you have set up your emulator/simulator correctly.

This is one way to run your app — you can also run it directly from within Android Studio and Xcode respectively.
