# 🔥 Firebase Todo Application

A real-time todo application built with Firebase, featuring user authentication and task management capabilities.

![image](https://github.com/user-attachments/assets/23d7e284-6fd2-4ff8-b775-22ad02f2a0ee)


## ⭐ Key Features

- User Authentication (Login/Register)
- Real-time task updates
- Task due dates
- Task filtering (All/Active/Completed)
- Task editing and deletion
- Progress tracking

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Firebase Authentication
- Firebase Realtime Database

## 📦 Installation

1. Clone the repository
```bash
git clone https://github.com/sameeraswijekoon/firebase-todo-app.git
```

2. Create a Firebase project at [Firebase Console](https://console.firebase.google.com)

3. Enable Authentication and Realtime Database in your Firebase project

4. Replace Firebase configuration in the HTML files with your own:
```javascript
const firebaseConfig = {
    apiKey: "your-api-key",
    authDomain: "your-domain.firebaseapp.com",
    databaseURL: "your-database-url",
    projectId: "your-project-id",
    storageBucket: "your-bucket.appspot.com",
    messagingSenderId: "your-sender-id",
    appId: "your-app-id",
    measurementId: "your-measurement-id"
};
```

5. Deploy to your preferred hosting service or run locally

## 📱 Screenshots

### Login Page
![image](https://github.com/user-attachments/assets/f31887e3-5fd4-4cf9-b8e7-0a11e1440ee3)

### Register Page
![image](https://github.com/user-attachments/assets/e2f8587e-1e46-4107-a28c-b2c9cb26ae4c)

### Task Dashboard
![image](https://github.com/user-attachments/assets/933fa60f-6ad9-4793-bc66-d51d4d0a0c02)



## 💻 Usage

### User Registration
- Navigate to register.html
- Fill in your details
- Click Register

### Task Management
- Add tasks with due dates
- Mark tasks as complete/incomplete
- Edit or delete tasks
- Filter tasks by status

## 📊 Database Structure

```
users/
├── [userId]/
    ├── info/
    │   ├── name
    │   ├── email
    │   └── createdAt
    │
    └── tasks/
        ├── [taskId]/
            ├── name
            ├── addDate
            ├── completeDate
            ├── completed
            └── completedDate
```

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👏 Acknowledgments

- Firebase Documentation
- Mozilla Developer Network
- Font Awesome for icons
