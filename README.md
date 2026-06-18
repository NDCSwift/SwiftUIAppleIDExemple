# 🍎 Sign in with Apple (SwiftUI)

A SwiftUI demo of Sign in with Apple — showing how to add the `SignInWithAppleButton`, handle the authorization result, and manage the authenticated user session.

---

## 🤔 What this is

This project demonstrates the complete Sign in with Apple flow in SwiftUI: presenting the `SignInWithAppleButton`, handling `ASAuthorizationAppleIDCredential` in the completion handler, extracting the user identifier and name, and storing the credential for session management. It covers both first-time sign-in and returning user flows.

## ✅ Why you'd use it

- **SignInWithAppleButton** — native SwiftUI button with correct styling
- **ASAuthorizationController** — handles the auth request and credential response
- **Credential parsing** — extracts user ID, full name, and email from `ASAuthorizationAppleIDCredential`
- **Session persistence** — stores the user identifier in Keychain for returning users
- **Capability setup** — shows which entitlements to enable in Xcode

## 📺 Watch on YouTube

[![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch%20the%20Tutorial-red?style=for-the-badge&logo=youtube)](https://youtu.be/ImhNHbqzoDE)

> This project was built for the [NoahDoesCoding YouTube channel](https://www.youtube.com/@noahdoescoding).

---

## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/NDCSwift/SwiftUIAppleIDExemple.git
cd SwiftUIAppleIDExemple
```

### 2. Open in Xcode
- Double-click `AppleIDExemple.xcodeproj`

### 3. Set Your Development Team
In Xcode: **TARGET → Signing & Capabilities → Team**

### 4. Enable Sign in with Apple Capability
In Xcode: **TARGET → Signing & Capabilities → + Capability → Sign in with Apple**

### 5. Update the Bundle Identifier
Change `com.example.MyApp` to a unique identifier (e.g., `com.yourname.AppleIDExample`).

---

## 🛠️ Notes

- Sign in with Apple requires a real Apple Developer account and a registered App ID.
- If you see a code signing error, check that Team, Bundle ID, and the capability are set.

## 📦 Requirements

- iOS 16+
- Xcode 15+
- Swift 5.9+
- Apple Developer account

---

📺 [Watch the guide on YouTube](https://youtu.be/ImhNHbqzoDE)
