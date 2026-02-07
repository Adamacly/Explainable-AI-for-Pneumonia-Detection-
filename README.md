# Pneumonia X-Ray XAI

Explainable AI-powered pneumonia detection system using Django, React, and Keras.

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
