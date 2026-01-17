KeepGoing is a social to-do list Flutter app that helps users stay productive by completing tasks together with friends.
Users can add tasks, send friend requests using email, track their own progress, and see their friends’ task progress in real time.
The app also sends notifications when friends complete tasks, creating motivation and accountability.

🎥 App Demo

▶️ Click to watch a short demo of the app:

https://github.com/harshchoudharryy/keepgoing/blob/main/screenshots/appicon.mp4


GitHub shows videos as clickable links (this is expected behavior).

✨ Features
✅ Personal Task Management

➕ Create, update, and delete daily tasks

✔️ Mark tasks as completed

📈 Track your own progress easily

👥 Friends System

📧 Add friends using their email address

🔄 Send & receive friend requests

✅ Accept or ❌ reject friend requests

👀 View your friends list

📊 Friends Progress Tracking

👥 See tasks created by your friends

✔️ Track which tasks your friends have completed

💪 Stay motivated by seeing others’ progress

🔔 Notifications

🔔 Get notified when:

A friend completes a task

A friend request is accepted

🚀 Helps maintain consistency and motivation

🔐 Authentication

🔒 Secure login and signup using Firebase Authentication

👤 User accounts managed with email & password

📱 App Screenshots
🏠 Home Screen

👥 Friends Screen

📝 Friend Tasks

📊 Task History

🏆 Leaderboard

🛠️ Tech Stack
Technology	Usage
🧩 Flutter	Frontend UI
🎯 Dart	Programming Language
🔐 Firebase Authentication	User Login & Signup
☁️ Cloud Firestore	Real-time Database
🔔 Firebase Cloud Messaging	Notifications
🔄 How the App Works

👤 User signs up or logs in

📝 User creates personal tasks

📧 User sends a friend request using email

✅ Friend accepts the request

👥 Both users can:

See each other’s tasks

Track task completion

🔔 Notifications are triggered when tasks are completed

⚙️ Installation & Setup
Prerequisites

Flutter SDK installed

Android Studio / VS Code

Firebase project setup

Steps
git clone https://github.com/harshchoudharryy/keepgoing.git
cd keepgoing
flutter pub get
flutter run

🔥 Firebase Configuration

Create a Firebase project

Enable:

🔐 Firebase Authentication (Email/Password)

☁️ Cloud Firestore

Download:

google-services.json (Android)

Place it inside:

android/app/


Run the app again 🚀

📂 Project Structure (Simplified)
lib/
 ├── screens/
 │    ├── login_screen.dart
 │    ├── home_screen.dart
 │    ├── friends_screen.dart
 │    ├── friend_tasks_screen.dart
 │
 ├── services/
 │    ├── auth_service.dart
 │    ├── firestore_service.dart
 │
 └── main.dart

🎯 Future Improvements

🔔 Push notifications using Firebase Cloud Messaging

⏰ Task deadlines & reminders

📰 Friend activity feed

🌙 Dark mode support

🖼️ Profile pictures for users

🤝 Contribution

Contributions are welcome! 🎉
Feel free to fork the repository, make improvements, and submit a pull request.

📄 License

📜 This project is licensed under the MIT License.

👨‍💻 Author

Harsh Kumar
Flutter Developer

📧 Email: harshchoudhary8789@gmail.com

🌐 GitHub: https://github.com/harshchoudharryy
