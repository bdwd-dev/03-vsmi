# VSMI Écosystème

Groupe sport multi-pôles

## Structure

```
03-vsmi/
├── backend/          # Express.js API (Port 3003)
│   ├── server.js
│   ├── package.json
│   └── db.json
├── web/              # React frontend (HTML + Babel standalone)
│   └── index.html
└── mobile/           # Flutter app
    └── lib/main.dart
```

## Démarrage

```bash
# Backend
cd 03-vsmi/backend
npm install
npm start

# Web — Ouvrir 03-vsmi/web/index.html dans un navigateur
# ou servir avec: npx serve 03-vsmi/web

# Mobile
cd 03-vsmi/mobile
flutter pub get
flutter run
```

## API

| Endpoint | Description |
|----------|-------------|
| GET /api/health | Health check |
| GET /api/stats | Statistiques |
