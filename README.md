# skilllab-project-
SINDHUSHREE.J - 1CX25CS207
Problem statement - AI Based Fake Identity & Document Screening system
Requirements:
WORK FLOW:
User
 ↓
Upload ID / Document
 ↓
OCR → Extract Name, DOB, ID details
 ↓
Document Validation
 ↓
AI Tampering Detection
 ↓
Cross-Document Matching
 ↓
Risk Score
 ↓
LOW / MEDIUM / HIGH

Technologies
Frontend: React + CSS
Backend: Python + FastAPI
Database: SQLite / PostgreSQL
OCR: Tesseract / PaddleOCR
AI: Python + OpenCV + Scikit-learn
Version Control: GitHub

structure:
AI-Identity-Screening/
│
├── frontend/
├── backend/
│   ├── api/
│   ├── services/
│   │   ├── ocr.py
│   │   ├── validation.py
│   │   ├── tampering.py
│   │   └── risk_engine.py
│   └── main.py
│
├── dataset/
│   └── synthetic_data/
│
├── tests/
├── docs/
├── README.md
└── .gitignore
MVP:
Upload → OCR → Extract details → Validate → Risk Score → Result
