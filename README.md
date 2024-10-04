# Swiftly - Flutter Chat App

**Swiftly** is a real-time chat application built with Flutter, utilizing Firebase for both frontend and backend. The app provides a smooth user experience with features like profile picture upload during sign-up, real-time messaging, and push notifications.

## Features

- **Firebase Authentication**: Sign up and log in users using Firebase.
- **Profile Picture Upload**: Users can take and upload a profile picture during the sign-in process.
- **Real-Time Chat**: Chats are saved in Firebase Firestore and can be accessed in real-time.
- **Push Notifications**: Users receive push notifications for new messages via Firebase Cloud Messaging (FCM).
- **Responsive UI**: The app is optimized for both iOS and Android platforms.

## Backend Overview

The entire backend of **Swiftly** is powered by Firebase, including:

- **Firebase Authentication** for managing user sign-in and sign-up.
- **Firebase Firestore** for real-time chat storage and syncing across devices.
- **Firebase Cloud Storage** for uploading and storing user profile pictures.
- **Firebase Cloud Messaging (FCM)** for sending and receiving push notifications.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/swiftly-chat-app.git
   cd swiftly-chat-app
   ```

2. Install dependencies:

   ```bash
   flutter pub get
   ```

3. Set up Firebase:

   - Go to [Firebase Console](https://console.firebase.google.com/).
   - Create a new project.
   - Add both iOS and Android apps to the project.
   - Download the `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) files and place them in the appropriate directories (`android/app` and `ios/Runner`).

4. Configure push notifications:

   - Enable Cloud Messaging in Firebase for push notifications.
   - Set up notification channels in Android (if necessary).

5. Run the app:

   ```bash
   flutter run
   ```

## Usage

- **Authentication**: Users can sign up or log in with email and password. During sign-up, they can also capture and upload a profile picture.
- **Chat**: Users can send and receive messages in real-time, with all chats being stored in Firebase Firestore.
- **Push Notifications**: Notifications are sent when users receive new messages using Firebase Cloud Messaging.

## Firebase Configuration

Ensure you have configured Firebase correctly with:

- **Authentication** for user sign-in.
- **Firestore** for chat storage.
- **Cloud Storage** for profile picture uploads.
- **Firebase Cloud Messaging (FCM)** for push notifications.

Update the `google-services.json` and `GoogleService-Info.plist` files with your Firebase project details.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit and push your changes (`git push origin feature-branch`).
5. Submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any questions or feedback, feel free to reach out:

- **Piyush**: [Your Email]

---

Let me know if you'd like to tweak anything else!
