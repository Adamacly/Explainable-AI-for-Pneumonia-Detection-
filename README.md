# Pneumonia X-Ray XAI

Explainable AI-powered pneumonia detection system using Django, React, and Keras.

## 📊 Model Performance

The trained Keras model demonstrates strong performance on pneumonia detection:

- **Test Accuracy**: 0.8989 (89.89%)
- **Test Precision**: 0.8687 (86.87%)
- **Test Recall**: 0.9414 (94.14%)

The high recall score indicates excellent sensitivity in detecting pneumonia cases, which is critical for medical diagnosis applications.

## 🚀 Quick Start

### Backend

```bash
python -m venv venv
venv\Scripts\activate  # Windows or source venv/bin/activate
pip install -r requirements.txt
cd backend_app
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

### Frontend

```bash
cd frontend_app
npm install
npm start
```

## 📍 Access

- **Backend** : http://localhost:8000
- **Admin** : http://localhost:8000/admin
- **Frontend** : http://localhost:3000

## 📁 Structure

```
├── backend_app/        # Django + REST API + Keras Model
│   ├── api/           # API Endpoints
│   ├── model/         # ML Model (.keras)
│   └── db.sqlite3     # Database
├── frontend_app/       # React + Tailwind
│   └── src/           # React Components
└── requirements.txt    # Python Dependencies
```

## ⚠️ Note

This project is for educational purposes only. Do not use for real diagnosis without proper regulatory approval.
