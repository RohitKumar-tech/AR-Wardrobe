# 👕✨ AR Wardrobe Assistant App

![Unity](https://img.shields.io/badge/Unity-3D%20AR-blue.svg?logo=unity)
![Firebase](https://img.shields.io/badge/Firebase-Backend-yellow.svg?logo=firebase)
![FastAPI](https://img.shields.io/badge/FastAPI-AI%20Agent-green.svg?logo=fastapi)
![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android-important?logo=apple&logo=android)
![License](https://img.shields.io/badge/License-MIT-brightgreen.svg)

> 🔮 Your **AI-powered Personal Stylist** in an **AR-driven Metaverse Wardrobe** 🌐👗

---

## 🧠 Project Vision

Imagine walking into your **virtual home**, interacting with appliances, and entering your **walk-in AR closet** where a **virtual version of you** tries on your outfits in real-time.

This app brings that imagination to life. Designed for both fashion lovers and tech enthusiasts, the **AR Wardrobe Assistant** combines **Augmented Reality**, **AI personalization**, and **interactive 3D environments** — all wrapped in a mobile app deployable on **Play Store** and **App Store**.

---

## 🏗️ Features

### 👤 Authentication & Security
- 🔐 Secure Email/Password Login
- 🔓 Google Sign-In (OAuth2 via Firebase)
- 📱 Forgot Password Recovery
- 🔍 Captcha-enabled Signup Form

### 🏠 Metaverse Home Navigation
- 🧍 Walk around a virtual 3D home
- 💡 Interact with smart appliances
- 🚪 Enter walk-in closet via realistic room transition

### 🧥 AR-Based Walk-in Closet
- 🧍‍♂️ AR model of user in undergarments (base avatar)
- 🧾 Filter clothes by category: Shirts, Jeans, Shoes, etc.
- 🪄 Try-on feature with live AR preview
- ➕ Add clothes via camera or photo upload
- ➖ Remove unwanted outfits with a tap

### 🧠 AI Personal Stylist (Custom Chatbot)
- 🤖 “What’s your plan today?” assistant
- 👗 Suggests outfits based on:
  - Event type (e.g. office, date, gym)
  - Mood/style (casual, formal, sporty)
  - Weather (optional)
- 🧠 Learns preferences over time

---

## ⚙️ Tech Stack Overview

| Layer            | Technology                                |
|------------------|--------------------------------------------|
| **AR Frontend**   | Unity3D + AR Foundation (ARKit/ARCore)     |
| **Auth & Storage**| Firebase Auth + Firestore + Firebase Storage |
| **AI Backend**    | FastAPI + LangChain or OpenAI              |
| **Avatars**       | ReadyPlayerMe, Mixamo                     |
| **App Platform**  | Android (Play Store), iOS (App Store)     |

---

## 🗂 Project Structure

```bash
ar-wardrobe-app/
├── unity-app/               # AR scenes, UI, avatars
├── firebase-config/         # Auth rules, Firestore setup
├── ai-stylist-backend/      # Python API for outfit suggestions
├── assets/                  # User avatars, clothing textures
├── docs/                    # Architecture, planning, day-wise logs
└── README.md

## Author

- Rohit kumar 