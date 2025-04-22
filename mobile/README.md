# ✈️ Cryptofly App

**Cryptofly** is a mobile app that enables peer-to-peer crypto payments using the Solana blockchain.  
It allows users to easily:

- Send/receive crypto via QR code
- Send crypto to phonebook contacts
- Request crypto from contacts

Built with React Native, `expo-router` and Solana's latest SDK (`@solana/kit`).

---

## 🛠️ Getting Started

### 🔗 Requirements
- Node.js >= 18
- Expo CLI (`npm install -g expo`)
- Xcode + iOS device or simulator (for iOS testing)
- (Optional) EAS CLI if you plan to build on the cloud

### 📦 Install dependencies

```bash
cd mobile
npm install
```

---

## How to run the app

### 1. First time: build and install on iPhone

Use this if you're setting up the app for the first time or added a native module (like SecureStore):

```bash
npm run ios:device
```

This will:

* Compile the app with expo-dev-client
* Install it on your physical iPhone
* Make it ready to load your local project

### 2. Daily use: start local dev server

Once the app is installed on your phone:
```bash
npx expo start --dev-client
```
This starts the Metro bundler and gives you a QR code.

* Scan the QR from the installed app (not Expo Go)
* Your code will load and refresh automatically

