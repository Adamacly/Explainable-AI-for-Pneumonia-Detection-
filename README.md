# Pneumonia X-Ray XAI

Système de détection de pneumonie par IA utilisant Django, React et Keras.

## � Installation rapide

### Backend

```bash
python -m venv venv
venv\Scripts\activate  # Windows ou source venv/bin/activate
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

## 📍 Accès

- **Backend** : http://localhost:8000
- **Admin** : http://localhost:8000/admin
- **Frontend** : http://localhost:3000

## 📁 Structure

```
├── backend_app/        # Django + API REST + Modèle Keras
│   ├── api/           # Endpoints API
│   ├── model/         # Modèle ML (.keras)
│   └── db.sqlite3     # Base de données
├── frontend_app/       # React + Tailwind
│   └── src/           # Composants React
└── requirements.txt    # Dépendances Python
```

## ⚠️ Note

Ce projet est à usage éducatif uniquement. Ne pas utiliser pour diagnostics réels sans approbation réglementaire.
