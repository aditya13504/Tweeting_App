# ✨ Tweeting App  
*A real-time Twitter-like app with Firebase integration for seamless data management.*

---

## Key Features  
- **Real-Time Updates**: See tweets immediately as they're posted.  
- **Firestore Integration**: Data stored and synced using Google Firebase.  
- **Interactive Tweets**: Like and delete tweets with ease.  
- **Modern UI**: Built with Jetpack Compose for smooth interactions.  

---

## 🛠️ Tech Stack  
- **Kotlin**: Primary programming language.  
- **Jetpack Compose**: For modern, declarative UI.  
- **Firebase Firestore**: Backend database for real-time data sync.  
- **Firebase Authentication**: Secure user authentication (planned).  

---

## 🚀 Getting Started  
```bash
# 1. Clone the Repository
git clone https://github.com/aditya13504/Tweeting_App.git

# 2. Setup Firebase  
- Create a Firebase project in the Firebase Console.  
- Add Android app with package name `com.example.tweetingapp`.  
- Download `google-services.json` and place it in the `app/` directory.  

# 3. Run the App  
- Connect an Android device or use an emulator.  
- Click the "Run" button in Android Studio.  
```
## 📱 How to Use

1. **Set Up Your Profile**:
   - **Username**: Enter your preferred username in the text field provided at the top of the screen.
   - **Profile**: (Future feature) Add a profile picture and bio for personalized identification.

2. **Write a Tweet**:
   - Compose your message in the text field labeled "What's happening?".
   - Keep it concise and relevant to engage your audience effectively.

3. **Post a Tweet**:
   - Click the **Tweet** button to publish your message.
   - Your tweet will immediately appear in the feed, visible to all users.

4. **Interact with Tweets**:
   - **Like**: Tap the heart icon to show appreciation for a tweet. The icon will turn blue when liked.
   - **Unlike**: Tap the heart icon again to remove your like.
   - **Delete**: Use the delete icon to remove your own tweets. This action is permanent.

---

## ⚙️ Data Storage (Firebase)

- **Real-Time Database**: The app leverages Firebase Firestore for seamless real-time data synchronization across all devices.
- **Cloud Storage**: User data, tweets, and interactions are securely stored and backed up in the cloud.
- **Efficiency**: Data retrieval and updates are optimized for speed, ensuring minimal latency even during peak usage.
- **Scalability**: The backend infrastructure automatically scales to accommodate a growing user base and increased activity.
- **Security**: Firebase provides robust security rules to protect user data and prevent unauthorized access.

## 🤝 Contributing
Contributions welcome! Submit issues or pull requests on GitHub.
