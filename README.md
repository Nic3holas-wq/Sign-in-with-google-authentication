# 🔐 Sign in with Google Authentication – Android (Jetpack Compose + Kotlin)

This project demonstrates how to implement **Google Sign-In** functionality in an Android app using **Jetpack Compose** and **Kotlin**. It enables users to sign in using their Google account, making authentication simple, fast, and secure.

---

## 📱 Features

- 🔒 Google OAuth Authentication
- ✅ Firebase integration
- 💡 Jetpack Compose UI
- 📦 Modular and clean project structure

---

## 📸 Screenshots

| Login Screen | Signed-In Screen |
|--------------|------------------|
| ![Login Screen](assets/login_screen.png) | ![Home Screen](assets/home_screen.png) |

> 📷 Add your screenshots inside an `assets/` folder and update the above paths.

---

## 🚀 Getting Started

### ✅ Prerequisites

- Android Studio (latest stable version)
- Firebase project with Android app registered
- Google OAuth client ID from Firebase Console

---

### 🔧 Setup Instructions

1. **Clone the repo**

   ```bash
   git clone https://github.com/Nic3holas-wq/Sign-in-with-google-authentication.git
   cd Sign-in-with-google-authentication
2. **Setup Firebase**
Create a Firebase project
Register your Android app in Firebase and download the google-services.json file.
Place google-services.json in your app/ directory.

3. **Enable Google Sign-In**
In Firebase Console → Authentication → Sign-in method → Enable Google provider.

4. **Build and Run**
Open the project in Android Studio
Sync Gradle and run the app on your device/emulator


**🛡️ Security Note**
Do not expose your Firebase credentials or OAuth client secrets in public repositories. Use .gitignore to exclude sensitive files like google-services.json.

**🤝 Contributing**
Got suggestions or improvements? Feel free to open an issue or pull request.
