# 🔒 PRIVATE CHAT

A secure real-time private chat application built with **HTML, CSS, JavaScript, Firebase Realtime Database, and AES-GCM Encryption**.

Users can create private rooms using secret tokens, exchange encrypted messages, lock conversations with passwords, monitor online users, and automatically delete chat history after 24 hours.

---

## ✨ Features

### 🔐 End-to-End Encryption

* AES-GCM encryption for all messages
* Messages are encrypted before storage
* Only users with the correct room credentials can decrypt messages

### 🏠 Private Token Rooms

* Create unique chat rooms using secret tokens
* Join existing rooms instantly
* No account registration required

### 🔒 Password Protected Rooms

* Lock rooms with custom passwords
* Restrict unauthorized access
* Open or lock rooms anytime

### ⚡ Real-Time Messaging

* Instant message delivery
* Firebase Realtime Database synchronization
* Live updates without page refresh

### 👥 Online User Tracking

* See how many users are currently online
* Automatic user disconnect detection

### ✍️ Typing Indicator

* Displays when another user is typing
* Real-time typing status updates

### 😀 Emoji Support

* Built-in emoji panel
* Quick emoji insertion

### 🗑 Auto Delete System

* Automatic database reset every 24 hours
* Messages are permanently removed
* Privacy-focused design

### 📱 Responsive Design

* Mobile-friendly interface
* Tablet and desktop support
* Modern glassmorphism UI

---

## 🛠 Technologies Used

* HTML5
* CSS3
* JavaScript (ES6 Modules)
* Firebase Realtime Database
* Firebase Hosting Ready
* Web Crypto API
* AES-GCM Encryption

---

## 📂 Project Structure

```text
PRIVATE-CHAT/
│
├── index.html
├── lock.png
└── README.md
```

---

## 🚀 How It Works

1. Enter your name
2. Enter a secret room token
3. Create or join a room
4. Optionally protect the room with a password
5. Start sending encrypted messages
6. Messages are stored securely in Firebase
7. All chat data automatically resets after 24 hours

---

## 🔧 Firebase Configuration

Replace the Firebase configuration with your own project credentials:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  databaseURL: "YOUR_DATABASE_URL",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

---

## 🔐 Security Features

* AES-GCM Message Encryption
* SHA-256 Password Hashing
* Private Token-Based Access
* Password-Protected Rooms
* Automatic Data Cleanup
* No Plaintext Message Storage

---

## 📸 Screenshots

Add screenshots here:

```text
screenshots/
├── home.png
├── chat-room.png
├── locked-room.png
└── mobile-view.png
```

---

## 🌟 Future Improvements

* File Sharing
* Voice Messages
* Dark/Light Theme Toggle
* Message Reactions
* Read Receipts
* User Profiles
* Push Notifications

---

## 👨‍💻 Developer

**Sayan Mahalanabish**

Technology Enthusiast | Web Developer | Programmer

GitHub: https://github.com/sayan08880

Portfolio: https://sayan08880.github.io/PORTFOLIO/

LinkedIn: https://in.linkedin.com/in/sayan-mahalanabish-4278571b6

---

## 📜 License

This project is open-source and available under the MIT License.

---

⭐ If you like this project, don't forget to star the repository!
