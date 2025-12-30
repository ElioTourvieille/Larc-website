# larc-website

Site web de l'école l'Arc - Projet de refonte

## 📋 À propos du projet

Refonte complète du site web de l'école l'Arc avec pour objectifs :
- Modernisation de l'interface
- Amélioration de l'expérience utilisateur
- Performance et accessibilité optimisées

## 🛠️ Technologies

- **Framework** : Next.js
- **CMS** : Payload
- **Styling** : Tailwind + ShadCN
- **Hébergement** : Infomaniak

## 🚀 Installation et développement
```bash
# Cloner le repository
git clone [URL]

# Installer les dépendances
npm install

# Lancer en développement
npm run dev
```

## 👥 Équipe

- **Development/Backend** : [Eric Tourvieille]
- **Design/Frontend** : [Thoma Boehi]
- **Project Manager** : [Chadi Chammout]

## 📁 Structure du projet
```
larc-website/
├── src/
│   ├── app/
│   │   ├── (frontend)/              # 🎨 Frontend - Votre collègue
│   │   │   ├── [slug]/             # Pages dynamiques
│   │   │   ├── posts/              # Blog/Actualités
│   │   │   ├── _components/        # Composants réutilisables
│   │   │   └── layout.tsx
│   │   └── (payload)/              # ⚙️ Admin Payload - Vous
│   │       ├── admin/
│   │       └── api/
│   ├── blocks/                      # 📦 Blocs pour le layout builder
│   │   ├── ArchiveBlock/
│   │   ├── CallToAction/
│   │   ├── Content/
│   │   ├── FormBlock/
│   │   └── MediaBlock/
│   ├── collections/                 # 🗄️ Collections Payload - Vous
│   │   ├── Categories.ts
│   │   ├── Media.ts
│   │   ├── Pages.ts
│   │   ├── Posts.ts
│   │   └── Users.ts
│   ├── fields/                      # 🔧 Champs réutilisables
│   ├── access/                      # 🔐 Access control
│   ├── payload.config.ts            # ⚙️ Config principale
│   └── utilities/                   # 🛠️ Utilitaires
├── public/
├── docker-compose.yml               # 🐳 PostgreSQL local
├── package.json
└── README.md
```

## 🔄 Workflow Git

- `main` : Branche de production (protégée)
- `develop` : Branche de développement
- `feature/*` : Nouvelles fonctionnalités
- `fix/*` : Corrections de bugs

## 📝 Convention de commits
```
feat: nouvelle fonctionnalité
fix: correction de bug
refactor: refactoring du code
style: modifications CSS/UI
docs: documentation
chore: tâches de maintenance (config, dependencies)
```

**Exemples :**
```bash
git commit -m "feat: add responsive navbar with mobile menu"
git commit -m "fix: correct header alignment on mobile"
git commit -m "style: update color scheme to match brand guidelines"
```
