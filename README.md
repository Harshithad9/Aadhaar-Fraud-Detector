# Aadhaar Fraud Detection System

This project implements an AI-based system to detect forged or tampered Aadhaar cards using computer vision and deep learning techniques. It features a user-friendly frontend interface and a robust Flask backend for verification.

## 🚀 Features

* **AI-based Fraud Detection:** Utilizes a custom-trained YOLOv8 model for high-accuracy fraud pattern identification.
* **Verification Modes:**
    * **Single Image Verification:** Endpoint for uploading and analyzing one Aadhaar image at a time.
    * **Bulk Verification:** Supports uploading a ZIP file containing multiple images for batch processing.
* **Fraud Pattern Analysis:** Identifies possible fraud patterns such as:
    * Tampered text
    * Fake or missing QR codes
    * Manipulated photos
    * Edited background or overlays
    * Missing security features
* **Technology Stack:**
    * **Backend:** Flask (Python) with JSON APIs.
    * **Frontend:** HTML, CSS, and JavaScript.
    * **Model Integration:** YOLOv8.
* **Ease of Deployment:** Designed to be easy to customize and deploy.

## 🛠️ Installation

Follow these steps to set up and run the application locally.

🔮 Future Enhancements
Potential improvements for future development:

OCR-based Aadhaar information extraction for data cross-validation.

QR code validation and integrity check.

Integration of Deepfake detection models for advanced photo manipulation.

Development of an analytics dashboard to track fraud patterns and usage statistics.

📝 License
This project is licensed under the MIT License.
