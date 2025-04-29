
# 💬 Android Chat App – ChatVerse

An end-to-end real-time chat application built using **Kotlin** and **MVVM architecture**, backed by **Firebase** services. This app allows users to sign up, log in, send and receive one-on-one messages, receive push notifications, and manage their profiles—all within a responsive and modern interface.

This app is being further extended to integrate the **CometChat UI Kit** for more advanced messaging capabilities.

---

## 🚀 Key Features

- 🔐 **User Authentication**
  - Firebase Authentication (Email/Password)
  - Login, Signup, and Logout support

- 💬 **One-on-One Messaging**
  - Realtime chat using Firebase Realtime Database
  - Chat screens following MVVM pattern

- 🔔 **Push Notifications**
  - Firebase Cloud Messaging (FCM) for new message alerts

- 👤 **Profile Management**
  - View and edit user profile details

- ⚙️ **Settings and Preferences**
  - Update user information and preferences

- 🖌️ **Modern UI**
  - Clean, intuitive design following Material Design principles

---

## 🛠️ Tech Stack

| Layer           | Technology                          |
|------------------|--------------------------------------|
| Language         | Kotlin                               |
| Architecture     | MVVM                                 |
| Backend          | Firebase Authentication, Firestore   |
| Realtime DB      | Firebase Realtime Database           |
| Notifications    | Firebase Cloud Messaging (FCM)       |
| UI               | XML + Material Components            |
| IDE              | Android Studio (Arctic Fox or newer) |

---

## 🔧 Getting Started

### Step 1: Clone the Repository

```bash
git clone https://github.com/Deepshikha2004/ChatVerse.git
cd ChatVerse
```

### Step 2: Open in Android Studio

- Open Android Studio
- Click **"Open an Existing Project"**
- Select the root folder of this project (`ChatVerse/`)

### Step 3: Set Up Firebase

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new Firebase project
3. Download the `google-services.json` file from the project settings
4. Place it inside the `app/` folder of your Android project
5. Enable the following services in Firebase:
   - Firebase Authentication
   - Firebase Realtime Database or Firestore
   - Firebase Cloud Messaging (for push notifications)

### Step 4: Build & Run the App

- Sync Gradle and wait for dependencies to resolve
- Connect an emulator or physical device
- Click **Run**

---

## 💡 Future Enhancements

We plan to integrate the **[CometChat Pro UI Kit](https://www.cometchat.com/docs/android-uikit/overview)** to enhance chat functionality with the following features:

### 🔄 Planned Features with CometChat:

- ✅ Group Chats
- ✅ Message Reactions
- ✅ Media Sharing (Images, Files)
- ✅ Typing Indicators
- ✅ Read Receipts
- ✅ Voice and Video Calling
- ✅ In-app Presence (Online/Offline status)

