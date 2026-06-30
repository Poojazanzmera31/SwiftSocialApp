# SwiftSocialApp
# SwiftSocialApp

SwiftSocialApp is a social media application developed using **SwiftUI** for iOS. The application allows users to register, log in, create posts with text and images, view posts in a feed, manage their profile, and securely store data locally using JSON files.

## 📱 Features

- User Registration
- User Login & Logout
- Persistent User Authentication
- Home Feed displaying all posts
- Create Posts with Text and Images
- View Post Details
- Delete Own Posts
- User Profile Screen
- Local JSON Data Storage
- Clean MVVM Architecture
- SwiftUI-based Modern User Interface

---

## 🛠️ Technologies Used

- Swift
- SwiftUI
- MVVM Architecture
- Combine Framework
- UIKit (Image Picker)
- JSON Encoding & Decoding
- FileManager
- Xcode

---

## 🚀 Application Workflow

### 1. User Authentication

- New users can create an account.
- Existing users can log in using their email and password.
- Login status is saved locally, allowing users to remain logged in.

### 2. Home Feed

- Displays all posts.
- Shows the post creator information.
- Allows navigation to detailed post view.

### 3. Add Post

Users can:

- Write a text caption
- Select an image from the photo gallery
- Publish the post instantly

### 4. Profile

Users can:

- View profile information
- View their posts
- Delete their own posts
- Logout securely

---

## 💾 Local Storage

The application stores data locally using JSON files inside the application's Documents directory.

Stored Files:

- `users.json`
- `posts.json`
- `currentUser.json`

Images are also stored locally using FileManager.

---

## 🏗️ Architecture

The project follows the **MVVM (Model-View-ViewModel)** architecture.

- **Models** → Represents application data.
- **Views** → User Interface built with SwiftUI.
- **ViewModels** → Business logic and state management.
- **Services** → Local storage and file management.

---

## 📸 Main Screens

- Login Screen
- Registration Screen
- Home Feed
- Add Post Screen
- Post Detail Screen
- Profile Screen

---

## ▶️ How to Run

### Requirements

- macOS
- Xcode 15 or later
- iOS 16+ Simulator (recommended)

### Steps

1. Clone or download this repository.
2. Open `SwiftSocialApp.xcodeproj` in Xcode.
3. Select an iOS Simulator.
4. Press **Run (⌘ + R)**.
5. Register a new account.
6. Log in and start creating posts.

---

## 🔑 Key Functionalities

- User Authentication
- Local Data Persistence
- Image Upload from Gallery
- JSON File Management
- Session Management
- SwiftUI Navigation
- MVVM Design Pattern

---

## 📈 Future Enhancements

- Firebase Authentication
- Cloud Firestore Database
- Real-time Feed Updates
- Likes and Comments
- User Search
- Friend Requests
- Notifications
- Dark Mode Support
- Push Notifications
- Cloud Image Storage

---

## 👩‍💻 Developer

**Pooja**

### Technologies

- Swift
- SwiftUI
- MVVM
- Combine
- UIKit
- JSON
- FileManager

---

## 📄 License

This project is developed for educational and learning purposes.
