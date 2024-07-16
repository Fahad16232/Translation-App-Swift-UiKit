# Translation App

Translation App is an iOS application supporting user authentication via Firebase, theme switching, language selection, and advanced translation features.

## Features

- *User Authentication*: Register, log in, and sign out using email/password or Google sign-in.
- *Dark Mode*: Toggle between dark and light modes.
- *Profile Information*: View your display name, email, and profile image.
- *Language Selection*: Change the app's language from the settings.
- *Text Translation*: Translate text between multiple languages.
- *Text-to-Speech*: Convert translated text to speech.
- *Speech-to-Text*: Convert spoken words to text for translation.
- *Image-to-Text*: Extract text from images for translation.

## Requirements

- iOS 13.0+
- Xcode 12.0+
- Swift 5.0+

## Installation

1. Clone the repository:
    bash
    git clone https://github.com/yourusername/TranslationApp.git
    cd TranslationApp
    
2. Install dependencies:
    bash
    pod install
    
3. Open the .xcworkspace file in Xcode:
    bash
    open TranslationApp.xcworkspace
    
4. Configure Firebase:
    - Add your GoogleService-Info.plist file to the project.
5. Run the app on a simulator or device.

## Usage

- *Register*: Enter your details and tap "Register".
- *Log In*: Enter your email and password, then tap "Login".
- *Dark Mode*: Go to settings and toggle the dark mode switch.
- *Change Language*: Go to settings and select a language.
- *Text Translation*: Enter text and select the target language to translate.
- *Text-to-Speech*: Tap the speaker icon to hear the translated text.
- *Speech-to-Text*: Use the microphone icon to convert speech to text.
- *Image-to-Text*: Use the camera to capture text from images for translation.

