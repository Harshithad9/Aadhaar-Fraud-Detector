# 🚀 AI-Powered Aadhaar Document Verification & Fraud Detection Platform  
### (AadhaarAuth System)

---

## 📌 Overview
AadhaarAuth System is an AI-powered platform designed to automate Aadhaar document verification and detect fraud using advanced technologies like OCR, Deep Learning, and Computer Vision.

It ensures fast, accurate, and scalable identity verification for organizations such as banks, government agencies, telecom providers, and healthcare systems.

---

## ❗ Problem Statement
India’s Aadhaar system serves 1.4+ billion people, making it vulnerable to:
- Identity theft  
- Document forgery  
- Fraudulent KYC submissions  

### ⚠️ Limitations of Manual Verification
- Time-consuming (5–10 minutes per document)  
- Error-prone due to human fatigue  
- Not scalable  
- Inconsistent verification quality  

---

## 💡 Solution
AadhaarAuth automates verification using a multi-layer AI pipeline:
- AI OCR (Gemini 2.5 Flash) – Context-aware text extraction  
- YOLOv8 – Fraud/tampering detection  
- OpenCV – Image forensics  
- Verhoeff Algorithm – Aadhaar number validation  

---

## 🏗️ System Architecture
- Frontend → UI & Upload  
- Backend → API + Processing  
- AI Layer → OCR + Fraud Detection  
- Database → Storage & Results  

---

## 🛠️ Tech Stack

| Layer            | Technology |
|------------------|-----------|
| Frontend         | React 19 |
| Styling          | TailwindCSS |
| Animations       | Framer Motion |
| Backend          | Django |
| API              | Django REST Framework |
| AI / OCR         | Gemini 2.5 Flash |
| Object Detection | YOLOv8 |
| Computer Vision  | OpenCV |
| Authentication   | JWT |
| Database         | SQLite / Supabase |

---

## ✨ Key Features
- Drag & Drop Document Upload  
- AI-Powered OCR with context understanding  
- Multi-layer Fraud Detection  
- JWT-based Authentication  
- Real-time Dashboard & Analytics  
- Batch Processing (multiple documents)  
- Export results (Excel/CSV/JSON)  

---

## 🖥️ Application Screens
- Landing Page – Overview and features  
- Login Page – Secure authentication  
- Dashboard – Stats, upload, analytics  
- Document Analysis – Extracted data + fraud detection  
- Verification Results – Accept/Reject + export  

---

## 🧠 Core Innovations

### 🔹 Multi-Layer Fraud Detection
| Layer | Technology | Purpose |
|------|-----------|--------|
| 1 | YOLOv8 | Object-level tampering |
| 2 | OpenCV | Image forensics |
| 3 | Verhoeff | Aadhaar validation |

---

## ⚙️ Installation & Setup

### 1. Clone Repository
```bash
git clone https://github.com/your-username/aadhaar-auth.git
cd aadhaar-auth

### 2. cd backend
```bash
pip install -r requirements.txt
python manage.py runserver

