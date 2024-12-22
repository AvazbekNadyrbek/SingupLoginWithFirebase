# Task Management App with Firebase

This project is part of my learning journey in Flutter and Firebase integration. It's a task management application that allows users to create, manage, and track their tasks with various features.

## 🚀 Technologies Used

- **Flutter**: The primary framework for building the cross-platform application
- **Dart**: The programming language used for development
- **Firebase Authentication**: For user authentication and management
- **Cloud Firestore**: NoSQL database for storing task data
- **Firebase Storage**: For storing task-related images and files
- **Other Key Packages**:
  - `flex_color_picker`: For color selection in tasks
  - `image_picker`: For selecting images from device
  - `dotted_border`: For UI elements
  - `uuid`: For generating unique identifiers
  - `intl`: For date formatting

## 🎯 Features

- User authentication with Firebase
- Create new tasks with:
  - Title and description
  - Due date selection
  - Color coding
  - Image attachments
- Mark tasks as completed
- Real-time updates using Firebase
- Secure data storage and retrieval

## 🛠️ Setup Instructions

1. **Prerequisites**:
   - Flutter SDK
   - Firebase account
   - Android Studio/VS Code

2. **Installation**:
   ```bash
   # Clone the repository
   git clone [your-repo-url]

   # Navigate to project directory
   cd SingUpwithFirebase

   # Install dependencies
   flutter pub get
   ```

3. **Firebase Setup**:
   - Create a new Firebase project
   - Add your Android/iOS app in Firebase console
   - Download and add the `google-services.json`/`GoogleService-Info.plist`
   - Enable Authentication and Firestore in Firebase console

4. **Run the app**:
   ```bash
   flutter run
   ```

## 📚 Learning Outcomes

Through this project, I've learned:
- Flutter UI development
- State management in Flutter
- Firebase integration
- User authentication implementation
- Cloud storage and database operations
- Real-time data synchronization

## 🤝 Contributing

This is a learning project, but suggestions and improvements are always welcome!

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
