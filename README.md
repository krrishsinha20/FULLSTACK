# GAN-Based Low-Light Image Enhancement System

A full-stack web application that enhances low-light images using a Generative Adversarial Network (GAN) to improve brightness, contrast, and overall visibility.

---

## Overview

Low-light conditions degrade image quality, making it difficult for computer vision systems to perform accurately. This project provides a deep learning-based solution integrated into a full-stack application that allows users to upload images and receive enhanced outputs in real time.

---

## Key Features

* Image upload interface
* GAN-based image enhancement
* Real-time processing
* Side-by-side comparison (before vs after)
* Cloud storage integration
* Download enhanced images
* API-based architecture

---

## System Architecture

User Upload → React Frontend → FastAPI Backend → GAN Model → Storage → Database → Response

---

## Technology Stack

### Frontend

* React.js
* HTML5
* CSS3

### Backend

* FastAPI (Python)

### Deep Learning

* PyTorch
* Generative Adversarial Network (GAN)

### Database and Storage

* PostgreSQL
* Supabase Storage

### Deployment

* Netlify (Frontend)
* Hugging Face Spaces (Model and Backend)

---

## Working of the System

1. The user uploads a low-light image through the frontend interface.
2. The image is sent to the backend using REST API.
3. The GAN model processes the image and enhances it.
4. The enhanced image is generated and stored.
5. The processed image is returned and displayed to the user.

---

## API Endpoints

| Endpoint  | Method | Description             |
| --------- | ------ | ----------------------- |
| /upload   | POST   | Upload image            |
| /enhance  | POST   | Enhance image using GAN |
| /retrieve | GET    | Fetch stored images     |

---

## Evaluation Metrics

* PSNR (Peak Signal-to-Noise Ratio)
* SSIM (Structural Similarity Index)

These metrics are used to evaluate improvement in image quality.

---

## Testing

* Functional Testing
* API Testing
* End-to-End Testing

---

## Sample Output

(Add sample images here: before and after enhancement)

---

## Installation

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

## Deployment

* Frontend hosted on Netlify
* Backend and model deployed on Hugging Face Spaces
* Database managed using Supabase

---

## Future Enhancements

* Video enhancement
* Real-time processing
* Mobile application
* Integration with object detection systems

---

## References

* Goodfellow et al., Generative Adversarial Networks, 2014
* EnlightenGAN, IEEE TIP 2021
* Retinex-Net, CVPR 2019
* LLNet, Pattern Recognition 2017

---

## Contributors

* Khurinji Malar
* Krrish Sinha
* Sukhada Dhingra
* Karan Rekhan

---

## GitHub Repository

(Add your repository link here)
