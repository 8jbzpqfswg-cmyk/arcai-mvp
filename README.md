# ArcAI MVP
Basketball shot analysis app: FastAPI backend + Expo/React Native frontend.

## Backend
```bash
cd backend
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

## Frontend
```bash
cd frontend
npm install
npx expo start
```

Set `EXPO_PUBLIC_API_BASE=http://<LAN-IP>:8000`.
