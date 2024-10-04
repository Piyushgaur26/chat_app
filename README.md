# Swiftly - Flutter Chat App

**Swiftly** is a real-time chat application built with Flutter, utilizing Firebase for authentication, chat storage, and push notifications. It offers a smooth user experience with features like profile picture upload during sign-up and push notifications for new messages.

## Features

- **Firebase Authentication**: Sign up and log in users using Firebase.
- **Profile Picture Upload**: Users can take and upload a profile picture during the sign-in process.
- **Real-Time Chat**: Chats are saved in Firebase and can be accessed in real-time.
- **Push Notifications**: Users receive push notifications for new messages.
- **Responsive UI**: The app is optimized for both iOS and Android platforms.

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
- **Chat**: Users can send and receive messages in real-time, with all chats being stored in Firebase.
- **Push Notifications**: Notifications are sent when users receive new messages.

## Firebase Configuration

Ensure you have configured Firebase correctly with authentication, Firestore for chat storage, and Firebase Cloud Messaging (FCM) for push notifications. Update the `google-services.json` and `GoogleService-Info.plist` files with your Firebase project details.

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

This is a customizable template based on your app features. Let me know if you’d like any specific details added or changes made!
