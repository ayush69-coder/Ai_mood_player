# 🎵 AI Mood Player

An intelligent web application that detects user mood using facial expressions and recommends songs accordingly.

---

## 🚀 Overview

AI Mood Player is a full-stack application built using **React.js**, **Node.js**, and **OpenCV**.
It captures user images, analyzes facial expressions, detects mood, and recommends songs based on the detected emotion.

---

## 🧠 How It Works

1. User opens the web app
2. Captures image via camera
3. Image is uploaded using **ImageKit**
4. Backend processes the image using **OpenCV**
5. Mood is detected (Happy, Sad, Angry, etc.)
6. Songs are recommended accordingly 🎶

---

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML5, CSS3, JavaScript

### Backend

* Node.js
* Express.js

### AI / Image Processing

* OpenCV

### Media Storage

* ImageKit

---

## ✨ Features

* 📸 Real-time image capture
* 😊 Mood detection using AI
* 🎵 Smart song recommendation
* ☁️ Cloud image storage (ImageKit)
* ⚡ Fast and responsive UI

---

## 📂 Project Structure

```
Ai-Mood-Player/
│
├── frontend/        # React app
├── backend/         # Node.js server
├── models/          # ML / OpenCV logic
├── assets/          # Images / static files
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/Ai_mood_player.git
cd Ai_mood_player
```

### 2️⃣ Install dependencies

#### Frontend

```bash
cd frontend
npm install
npm start
```

#### Backend

```bash
cd backend
npm install
npm start
```

---

## 🔐 Environment Variables

Create a `.env` file in backend:

```
IMAGEKIT_PUBLIC_KEY=your_key
IMAGEKIT_PRIVATE_KEY=your_key
IMAGEKIT_URL_ENDPOINT=your_url
```

---

## 🎯 Future Improvements

* 🎧 Spotify API integration
* 📊 Better mood accuracy with deep learning
* 📱 Mobile app version
* 🔐 User authentication system

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork and improve the project.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Ayush Srivastava**

* GitHub: https://github.com/ayush69-coder

---

