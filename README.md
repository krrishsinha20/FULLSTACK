# 🌙 GAN-Based Low-Light Image Enhancement System

A full-stack web application that enhances low-light images using a **Generative Adversarial Network (GAN)** to improve brightness, contrast, and overall visibility.

---

## 🚀 Overview

Low-light conditions often degrade image quality, making it difficult for computer vision systems to perform accurately. This project provides a **deep learning-based solution** integrated into a full-stack application that allows users to upload images and receive enhanced outputs in real time.

---

## 🧠 Key Features

* 📤 Image Upload Interface
* 🤖 GAN-based Image Enhancement
* ⚡ Real-time Processing
* 🖼️ Side-by-side Comparison (Before vs After)
* ☁️ Cloud Storage Integration
* 📥 Download Enhanced Images
* 🔗 API-based Architecture

---

## 🏗️ System Architecture

User Upload → React Frontend → FastAPI Backend → GAN Model → Storage → Database → Response

---

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML5
* CSS3

### Backend

* FastAPI (Python)

### Deep Learning

* PyTorch
* GAN (Generator + Discriminator)

### Database & Storage

* PostgreSQL
* Supabase Storage

### Deployment

* Netlify (Frontend)
* Hugging Face Spaces (Model + Backend)

---

## ⚙️ How It Works

1. User uploads a low-light image via the frontend
2. Image is sent to backend through REST API
3. GAN model processes the image
4. Enhanced image is generated
5. Output is stored and returned to user

---

## 📡 API Endpoints

| Endpoint    | Method | Description             |
| ----------- | ------ | ----------------------- |
| `/upload`   | POST   | Upload image            |
| `/enhance`  | POST   | Enhance image using GAN |
| `/retrieve` | GET    | Fetch stored images     |

---

## 📊 Evaluation Metrics

* **PSNR (Peak Signal-to-Noise Ratio)**
* **SSIM (Structural Similarity Index)**

These metrics validate improvement in image quality.

---

## 🧪 Testing

* Functional Testing
* API Testing
* End-to-End Testing

---

## 📷 Sample Output

*(Add your images here)*

* Before Enhancement
* After Enhancement

---

## 📦 Installation

### Clone Repository

```bash
git clone https://github.com/your-username/low-light-enhancement.git
cd low-light-enhancement
```

### Backend Setup

```bash
pip install -r requirements.txt
uvicorn main:app --reload
```

### Frontend Setup

```bash
npm install
npm start
```

---

## 🌐 Deployment

* Frontend: Netlify
* Backend + Model: Hugging Face Spaces
* Database: Supabase

---

## 📈 Future Enhancements

* 🎥 Video enhancement support
* ⚡ Real-time streaming
* 📱 Mobile application
* 🔍 Integration with object detection

---

## 📚 References

* Goodfellow et al., *Generative Adversarial Networks*, 2014
* EnlightenGAN, IEEE TIP 2021
* Retinex-Net, CVPR 2019
* LLNet, Pattern Recognition 2017

---

## 👨‍💻 Contributors

* Khurinji Malar
* Krrish Sinha
* Sukhada Dhingra
* Karan Rekhan

---

## 🔗 GitHub Repository

(Add your repo link here)

---

## ⭐ If you like this project, give it a star!
