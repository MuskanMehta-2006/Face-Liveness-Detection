# 🧠 Face Liveness Detection

This project is a browser-based **face liveness detection system** built using React and TensorFlow.js. It identifies whether the user in front of the camera is a real person or a spoof (e.g., photo, video, or mask).

---

## 🚀 Features

- ✅ Real-time face liveness detection
- ✅ Uses a TensorFlow.js model (`model.json` and shard binaries)
- ✅ Runs completely in-browser
- ✅ Built with React.js
- ✅ No server/backend required

---

## 📂 Project Structure

```
📁 Face-Liveness-Detection
├── App.js
├── App.css
├── App.test.js
├── index.js
├── index.css
├── logo.svg
├── model.json
├── group1-shard1of3.bin
├── group1-shard2of3.bin
├── group1-shard3of3.bin
├── reportWebVitals.js
└── setupTests.js
```

---

## 🛠️ Getting Started

### Prerequisites

- Node.js and npm installed

### Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/MuskanMehta-2006/Face-Liveness-Detection.git
cd Face-Liveness-Detection
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm start
```

Now visit `http://localhost:3000` in your browser to test the app.

---

## 💡 How It Works

- Accesses your webcam using `getUserMedia`
- Processes video frames using a TensorFlow.js model
- Predicts whether the face is **real** or **fake**
- Outputs the result on the UI instantly

---

## 📌 Use Cases

- Aadhaar authentication
- Attendance systems
- Secure login portals
- Anti-spoofing in online exams or banking apps

---

## 📈 Future Improvements

- Aadhaar face matching integration
- Improved spoof detection for videos/masks
- Backend support for logging and analytics
- Deployment via Vercel or Firebase

---

## 👩‍💻 Author

**Muskan Mehta**  
🔗 [GitHub Profile](https://github.com/MuskanMehta-2006)
Liveness Detection Model
TensorFlow Keras Python Google Colab

FastAPI Express.js MongoDB

React JavaScript Tailwind CSS

A real-time, deep learning-based liveness detection and face verification platform designed for secure, fast, and browser-based identity authentication — optimized for low-end devices and Aadhaar-ready!

🚀 Overview
Face recognition is powerful, but without liveness detection, it’s vulnerable to spoof attacks. This project aims to bridge that gap using an intelligent, full-stack solution:

✅ Detects whether a face is real or spoofed (photo/video attack)
✅ Enables secure Aadhaar face verification
✅ Runs directly in web browsers using TensorFlow.js
✅ Optimized for low-end devices
🧠 Core Features
🧬 Deep Learning-Based Liveness Detection
Built using TensorFlow and Keras with high accuracy in differentiating live faces from spoof attempts.

🌐 Web Deployment via TensorFlow.js
Real-time inference in the browser — no server round-trips, ensuring speed and privacy.

⚡ Model Optimization
Applied quantization and pruning to reduce model size by 30% with zero compromise on accuracy.
Improved inference speed by 15% on low-end devices.

🛡️ Secure Face Verification Platform
Full-stack implementation for Aadhaar-level authentication:

Backend powered by FastAPI
Face matching using a ResNet model achieving 92% accuracy
👥 Tested and Verified
Deployed and tested with 30+ users to evaluate spoof resistance and usability.

🛠️ Tech Stack
Machine Learning / Deep Learning

TensorFlow
Keras
TensorFlow.js
ResNet
Backend

FastAPI
Express.js
MongoDB
Frontend

React.js
JavaScript
Tailwind CSS
📈 model performance
Face Liveness Screenshot

📸 Demo https://youtu.be/q5oJCUSrBRI
Watch Demo

👆 Click the thumbnail to see the liveness detection model in action!

🧠 How It Works
🕵️‍♂️ Liveness Detection
Deep CNN trained on real vs spoofed faces
Handles printed photos, digital screens, and replay attacks
Runs directly in-browser with TensorFlow.js
🧬 Face Matching
Backend face matcher using ResNet
Achieves ~92% accuracy on benchmark Aadhaar-like data
🚀 Optimization Techniques
🔧 Quantization to reduce float precision
✂️ Model pruning to remove redundant weights
⚡ Faster inference with reduced compute and memory footprint
🛠️ Tech Stack
Layer	Technology
ML/AI	TensorFlow, Keras, TensorFlow.js, ResNet
Backend	FastAPI, Express.js, MongoDB
Frontend	React.js, Tailwind CSS, JavaScript
DevOps/Tools	Git, VS Code, Postman
Clone the repo

git clone https://github.com/akhilRathour/liveness-Detection-model.git
---

**Project Structure
FaceLivelinessProject/
├── FaceLivelinessOnCode/
│   ├── backend/
│   │   ├── config/              # Configuration files (e.g., DB, environment)
│   │   ├── controllers/         # API logic and route controllers
│   │   ├── models/              # Database models or schemas
│   │   ├── routes/              # Route definitions
│   │   └── server.js            # Main backend entry point (Express server)
│   │
│   ├── frontend/
│   │   ├── public/              
│   │   │   ├── tf_model/        # TensorFlow.js model files
│   │   │   ├── tfjs_model/      # Alternate/converted model files
│   │   │   ├── favicon.ico
│   │   │   ├── index.html       # Main HTML template
│   │   │   ├── logo192.png
│   │   │   ├── logo512.png
│   │   │   ├── manifest.json
│   │   │   └── robots.txt
│   │   │
│   │   └── src/
│   │       ├── assets/          # Static assets (images, styles, etc.)
│   │       ├── components/      # Reusable React components
│   │       ├── context/         # React context for global state
│   │       ├── pages/           # Route-level React components
│   │       ├── App.css
│   │       ├── App.js           # Root React component
│   │       ├── App.test.js
│   │       ├── index.css
│   │       ├── index.js         # React entry point
│   │       ├── logo.svg
│   │       ├── reportWebVitals.js
│   │       └── setupTests.js
│
├── FaceLiveliness_ModelTraining.ipynb   # google collab file used for model training/inference/testing


---

## 📄 License

This project is open-source and available under the MIT License.
