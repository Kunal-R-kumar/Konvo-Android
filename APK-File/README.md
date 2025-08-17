# 📱 Konvo – WhatsApp Clone (Android, Java)

Konvo is a real-time messaging application built in **Java (Android)** that offers features like **email-based authentication, OTP login (Twilio), Cloudinary profile storage, and Firebase-powered real-time chat** with light/dark themes and modern UI.  

---

## 📲 Installation (APK)

1. Download the latest **Konvo APK** from the [Releases](./releases) section of this repository.  
2. Ensure your device runs **Android 7.0 (Nougat) or above**.  
3. On your Android phone:  
   - Go to **Settings > Security**  
   - Enable **Install from Unknown Sources** (if not already enabled).  
4. Open the downloaded APK and install it.  
5. Once installed, you can launch **Konvo** from your app drawer.  

---

## ⚠️ Important Notes

- **Phone Number Authentication**:  
  - Konvo uses **Twilio** for phone-based OTP login.  
  - Due to **limited free credits** on Twilio, **phone authentication may not work** in this public build.  
  - You can still use **Email Signup/Login** for accessing the app.  

- **Minimum Requirements**:  
  - Android **7.0 (Nougat)** or above  
  - Active Internet connection (Wi-Fi or Mobile Data)  

---

## 🚀 Usage Instructions

1. **Sign Up**  
   - Create a new account using your **email**.  
   - Verify your email and set up your profile picture (stored securely in **Cloudinary**).  

2. **Login**  
   - Use your registered email & password to log in.  
   - (Phone OTP login is available but may not work due to Twilio limitations).  

3. **Chat**  
   - Start real-time conversations powered by **Firebase Realtime Database**.  
   - Messages are first stored on the server and synced across devices.  
   - Switch between **Light and Dark themes** from the app settings.  

4. **Profile Management**  
   - Upload or update your profile picture.  
   - Profile images are saved securely using **Cloudinary**.  

---

## 🛠️ Tech Stack

- **Language**: Java (Android)  
- **Backend/Database**: Firebase & node jS for phone authentication 
- **Authentication**: Firebase Email Auth, Twilio OTP (limited)  
- **Cloud Storage**: Cloudinary  
- **UI**: Material Design (Light/Dark Themes)  

---

## 👨‍💻 Author

_Developed by **Kunal R Kumar**  
📧 **kkumar021104@gmail.com**_

---
