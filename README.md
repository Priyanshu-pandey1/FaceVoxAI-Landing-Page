# FaceVoxAI 👁️🎙️

> **An advanced, multimodal AI-powered attendance system utilizing Face Recognition and Voice Biometrics.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-FaceVoxAI-blue?style=for-the-badge&logo=vercel)](https://facevoxai.vercel.app/)
[![Developer](https://img.shields.io/badge/Developer-Priyanshu%20Pandey-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/priyanshu-pandey-data/)

---

## 📖 Overview

**FaceVoxAI** (formerly SnapClass) is a next-generation attendance and identity verification platform. By combining high-accuracy facial recognition with voice biometric analysis, it creates a robust, spoof-resistant authentication process. The project utilizes a modern Python backend (Streamlit/Flask) and is integrated with Supabase for secure data management.

**Check out the live landing page here:** [https://facevoxai.vercel.app/](https://facevoxai.vercel.app/)

---

## ✨ Key Features

*   **Multimodal Biometrics:** Verifies user identity using both facial features and voiceprints for maximum security.
*   **Face Recognition:** Built on `dlib` and `face_recognition` models for fast and accurate face embeddings.
*   **Voice Biometrics:** Utilizes `librosa` and `resemblyzer` to extract and verify unique audio signatures.
*   **Secure Authentication:** Secure password hashing using `bcrypt` and remote database management via `Supabase`.
*   **QR Code Generation:** Dynamic QR code generation for quick user actions using `segno`.
*   **Modern Web Interface:** A sleek, user-friendly frontend deployed seamlessly on Vercel.

---

## 🛠️ Tech Stack

### Frontend & Deployment
*   **Web Framework:** Streamlit & Flask
*   **Languages:** HTML, CSS, Python
*   **Hosting:** Vercel

### Core AI / Machine Learning
*   **Face Analysis:** `dlib-bin`, `face_recognition_models`, `scikit-learn`
*   **Audio/Voice Analysis:** `librosa`, `resemblyzer`

### Database & Security
*   **Database:** Supabase
*   **Authentication:** `bcrypt`

### Utilities
*   **Data Handling:** `numpy`, `pandas`
*   **Image & Media Processing:** `Pillow` (PIL)
*   **QR Codes:** `segno`

---

## 🚀 Local Installation & Setup

To run FaceVoxAI on your local machine, follow these steps:

### 1. Clone the Repository
```bash
git clone [https://github.com/Priyanshu-pandey1/FaceVoxAI.git](https://github.com/Priyanshu-pandey1/FaceVoxAI.git)
cd FaceVoxAI
