# 🎥 YouTube Clone - A Custom Video Streaming Platform

Welcome to the **YouTube Clone** project! This is a full-stack video streaming platform built to demonstrate key real-world features such as **multi-quality video playback**, **download restrictions**, **Razorpay payment integration**, and a **gesture-based custom video player**.

> 🚀 Developed by [Naqeeb Ansari](https://github.com/naqeebansari2004)

---

## 🌟 Features

### 1. 🔁 Multi-Quality Video Playback
- Supports 320p, 480p, 720p, and 1080p resolutions.
- Users can switch video quality on the fly — just like YouTube.
- Adaptive streaming ensures smooth playback across devices.

### 2. 💾 Video Download System with Premium Unlock
- Users can download **1 video per day** for free.
- All downloads appear under the **"Downloads"** tab in the user's profile.
- Want more? Unlock unlimited downloads with a **Premium Plan** using **Razorpay (Test Mode)** integration.
- Razorpay handles payment flow — once successful, unlimited access is granted.

### 3. 🎮 Custom Gesture-Based Video Player
An immersive experience using modern gesture controls:
- **Double-tap right** → ⏩ Skip forward 10 seconds  
- **Double-tap left** → ⏪ Skip backward 10 seconds  
- **Single-tap center** → ⏸️ Pause or resume playback  
- **Triple-tap center** → ⏭️ Play next video  
- **Triple-tap right** → ❌ Exit the app  
- **Triple-tap left** → 💬 Open comment section

---

## 🧩 Components Overview

### Frontend
- **Client App** (`/client`)
  - Built with **React.js**
  - Custom video player UI
  - Responsive design
  - Razorpay integration

### Backend
- **Server API** (`/server`)
  - Built with **Node.js + Express**
  - Handles video metadata, authentication, download tracking, and Razorpay webhook
  - MongoDB for database storage

---

## 🛠️ Tech Stack

| Frontend        | Backend        | Database | Payment |
|-----------------|----------------|----------|---------|
| React.js        | Node.js        | MongoDB  | Razorpay (test mode) |
| HTML/CSS        | Express.js     | Mongoose |         |

---

## 📸 Screenshots

> ![Screenshot (42)](https://github.com/user-attachments/assets/11e54118-be71-4ec9-907f-9e19ac3ac325)


---

## 💡 Future Enhancements
- Add user comments and likes.
- Video recommendation engine.
- Admin dashboard for managing uploads and users.

---

## 🔗 Live Demo

*(If deployed, add link here — e.g., Vercel, Netlify, or Render)*

---

## 📥 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/naqeebansari2004/YouTube-Clone.git

# Go to client and install dependencies
cd client
npm install

# Go to server and install dependencies
cd ../server
npm install

# Start both servers (you can use tools like concurrently or run in separate terminals)
npm start
