# 👤 RecognizeMe - Real-Time Face Detection & Expression Recognition

**RecognizeMe** is a browser-based real-time face recognition project built using **face-api.js**. It runs entirely in the browser and uses your webcam to detect faces, identify facial landmarks, and recognize human expressions on the fly — no backend required!

---

## 🚀 Features

- 🔍 Real-time **face detection**
- 📌 Accurate **facial landmark** recognition (eyes, nose, mouth, etc.)
- 😊 Recognizes **facial expressions** like happy, sad, surprised, angry, etc.
- 🧠 Runs fully in-browser using **face-api.js**
- 🧩 Lightweight, extendable, and perfect for demos or real applications

---

## 🛠️ Technologies Used

- **JavaScript**
- **face-api.js**
- **HTML5 Video API**
- **Canvas API**

---

## 📁 Project Structure
RecognizeMe
│
├── /models # Pre-trained face-api.js models (downloaded separately)
├── index.html # Main HTML page
├── script.js # JS logic for face detection & expressions
└── style.css # Optional styling

## 2. Download the FaceAPI Models
Download and place these in a /models directory in the project root:
. tiny_face_detector_model
. face_landmark_68_model
. face_recognition_model
. face_expression_model

🔗 Download from: https://github.com/justadudewhohacks/face-api.js-models

## 🔐 Permissions
Ensure you allow webcam access when prompted by the browser.

