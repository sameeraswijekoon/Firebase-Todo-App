# Firebase Todo App 🚀

## Description 📋
A modern, responsive todo application built with HTML, JavaScript, and Firebase. Features real-time updates, user authentication, and task management with due dates.

## Features ⚙️
- **User Authentication** (Register/Login) 🔒
- **Real-time Task Updates** using Firebase Realtime Database 🌐
- **Task Creation** with due dates 📅
- **Task Status Tracking** (Active/Completed) ✅❌
- **Task Filtering System** 🔍
- **Edit and Delete Tasks** ✏️🗑️
- **Responsive Design** 📱💻
- **Remaining Tasks Counter** 📊
- **Due Date Tracking** with overdue status ⏰

## Technologies Used 🛠️
- **HTML5** 🌍
- **CSS3** 🎨
- **Vanilla JavaScript** 💻
- **Firebase Authentication** 🔑
- **Firebase Realtime Database** 🔥

## Project Structure 📂
├── index.html # Login page ├── register.html # Registration page └── dashboard.html # Main todo application


## Firebase Setup ⚡
1. Create a new Firebase project at [Firebase Console](https://console.firebase.google.com) 🎮
2. Enable Email/Password Authentication:
   - Go to Authentication → Sign-in methods 🧑‍💻
   - Enable Email/Password provider 🔑
3. Set up **Realtime Database**:
   - Go to Realtime Database 📊
   - Create database in test mode 🧪
4. Replace Firebase configuration in all HTML files:
```javascript
const firebaseConfig = {
    apiKey: "your-api-key",
    authDomain: "your-auth-domain",
    databaseURL: "your-database-url",
    projectId: "your-project-id",
    storageBucket: "your-storage-bucket",
    messagingSenderId: "your-messaging-sender-id",
    appId: "your-app-id"
};
