# Flutter Speech-to-Text App

This is a simple Flutter application that demonstrates the use of the `speech_to_text` package to
implement speech recognition functionality. The app listens to speech input and converts it into
text.

## Getting Started

To get started with this project, follow these steps:


### Installation

1. **Clone the Repository**
    - Clone this repository to your local machine or download the source code.

2. **Install Dependencies**
    - Navigate to the project root directory.
    - Run `flutter pub get` to install the required dependencies.

### Running the App

- Open the project in your preferred Flutter IDE or editor.
- Run the app using the `flutter run` command.
- Ensure you have an emulator running or a device connected.

## Features

- Speech recognition: Converts spoken words into text.
- Simple UI: A button to start/stop listening and a text area to display the recognized words.

## Permissions

- **Android**: You might need to add microphone permissions in your `AndroidManifest.xml`:

    ```xml
    <uses-permission android:name="android.permission.RECORD_AUDIO"/>
    <uses-permission android:name="android.permission.INTERNET"/>
    ```

- **iOS**: Add the following keys to your `Info.plist` file:

    ```xml
    <key>NSMicrophoneUsageDescription</key>
    <string>This app needs access to the microphone for voice input</string>
    <key>NSSpeechRecognitionUsageDescription</key>
    <string>This app needs access to speech recognition for processing your voice input</string>
    ```

