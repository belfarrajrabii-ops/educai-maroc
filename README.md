# EDUCAI Maroc 🎓

Plateforme d'assistance scolaire intelligente basée sur l'IA pour les collèges et lycées du Maroc.

## 🎯 Vision

Devenir l'assistant scolaire intelligent de référence au Maroc en centralisant l'accompagnement pédagogique et l'orientation scolaire dans une seule plateforme.

## ✨ Fonctionnalités MVP

### Assistant IA pour les élèves
- 💬 Chat IA bilingue (Français/Arabe)
- 📚 Réponses aux questions scolaires
- 📝 Explication de leçons
- ✅ Génération de quiz interactifs
- 🎯 Aide aux exercices

### Orientation scolaire
- 🏫 Présentation des filières lycée
- 📊 Recommandations basées sur résultats
- 🎓 Informations universités marocaines
- 📋 Conseil d'orientation personnalisé

## 🏗️ Architecture

```
Frontend (Next.js)
    ↓
Backend (Node.js/Express)
    ↓
Supabase (PostgreSQL + Auth)
    ↓
IA (Hugging Face/Mistral)
```

## 🚀 Démarrage rapide

### Prérequis
- Node.js 18+
- Git
- Compte Supabase (gratuit)

### Installation

```bash
# Clone le repo
git clone https://github.com/belfarrajrabii-ops/educai-maroc.git
cd educai-maroc

# Installation dépendances frontend
cd frontend
npm install

# Installation dépendances backend
cd ../backend
npm install

# Configuration .env (voir .env.example)
cp .env.example .env
# Complétez avec vos clés API
```

### Déploiement

**Frontend (Vercel)**
```bash
npm install -g vercel
vercel
```

**Backend (Render ou Railway)**
- Push sur GitHub
- Connectez Render/Railway au repo

## 📁 Structure du projet

```
educai-maroc/
├── frontend/
│   ├── app/
│   │   ├── page.tsx
│   │   ├── auth/
│   │   ├── dashboard/
│   │   └── chat/
│   ├── components/
│   ├── public/
│   └── package.json
├── backend/
│   ├── routes/
│   │   ├── auth.js
│   │   ├── chat.js
│   │   ├── quiz.js
│   │   └── orientation.js
│   ├── middleware/
│   ├── controllers/
│   ├── server.js
│   └── package.json
├── database/
│   └── schema.sql
├── docs/
│   ├── SETUP.md
│   ├── API.md
│   └── DEPLOYMENT.md
└── .env.example
```

## 🔑 Variables d'environnement

Voir `.env.example` pour tous les paramètres nécessaires.

## 📚 Documentation

- [Guide de Setup](./docs/SETUP.md)
- [Documentation API](./docs/API.md)
- [Guide de Déploiement](./docs/DEPLOYMENT.md)

## 👥 Utilisateurs MVP

- ✅ Élèves (chat IA + orientation)
- 📅 Parents (à venir - Phase 2)
- 👨‍🏫 Enseignants (à venir - Phase 2)
- 🏛️ Administration (à venir - Phase 2)

## 💰 Coût initial

| Service | Coût | Notes |
|---------|------|-------|
| Vercel | Gratuit | Hosting frontend |
| Supabase | Gratuit | DB + Auth (500MB) |
| Hugging Face | Gratuit | IA (modèles open source) |
| **TOTAL** | **0€** | Phase validation |

## 🗺️ Roadmap

- **Phase 1** : Chat IA + Authentification (Semaine 1-2) ✅
- **Phase 2** : Quiz + Orientation (Semaine 3-4)
- **Phase 3** : Module Parents (Semaine 5-6)
- **Phase 4** : Dashboard Admin (Semaine 7-8)

## 🔐 Authentification

- Email + Mot de passe (Supabase Auth)
- Google OAuth
- Stockage sécurisé des données

## 📱 Plateforme

- ✅ Web (Next.js)
- 📅 Mobile (React Native - Phase 2)
- 📅 WhatsApp Bot (Phase 3)

## 📧 Contact

Pour toute question : belfarrajrabii@gmail.com

## 📄 Licence

MIT

---

**Made with ❤️ for Moroccan Students**
