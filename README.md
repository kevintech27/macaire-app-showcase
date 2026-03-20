# 🏅 MACAIRE - Plateforme de Coaching Sur-Mesure

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-181818?style=for-the-badge&logo=supabase&logoColor=3ECF8E)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**MACAIRE Coaching v1.0 est un SaaS complet de coaching sportif en ligne conçu pour optimiser le suivi des athlètes avec une interface premium, pour un gain de temps et d'énergie maximal.**

</div>

---

## ✨ Fonctionnalités Clés

- 🔒 **Authentification Sécurisée** : Intégration de *Supabase Auth*, confirmation par e-mail avec serveur SMTP Hostinger, et processus complet comprenant la récupération de mot de passe.
- 👥 **Gestion des Rôles Intelligente** : Séparation stricte des accès et des interfaces entre **Coach** et **Athlète** grâce aux Row Level Security (RLS) policies.
- 🚀 **Flux d'Onboarding Dynamique** : Accueil interactif et structuré pour guider les nouveaux clients lors de leur arrivée sur la plateforme.
- 📊 **Dashboard Interactif** : Hub central incluant le suivi du poids, de la difficulté perçue (RPE), les check-ins hebdomadaires, et la vision de la progression sur 12 mois grâce à des graphiques fluides.
- 🎨 **UI/UX Premium** : Interfaces modernes, lisibles et haut-de-gamme conçues avec *Tailwind CSS* et agrémentées des icônes de *Lucide React*.

## 🛠️ Stack Technique

### Frontend
- **Framework** : React (via Vite)
- **Styling** : Tailwind CSS
- **Routage** : React Router

### Backend / BaaS
- **Base de Données & Infrastructure** : Supabase (PostgreSQL, Auth, RLS Policies)

### Déploiement & Cloud cloud
- **Hébergement & CI/CD** : Vercel
- **Domaine & Serveur Mail** : Hostinger

## 💻 Installation en local (Guide Développeurs)

### Prérequis
- **Node.js** (v18 ou supérieur recommandé)
- **npm** (Node Package Manager)

### Démarrage rapide

1. **Cloner le projet et naviguer dans le dossier**
   ```bash
   git clone <URL_DU_REPO>
   cd fitness-web-app
   ```

2. **Installer les dépendances**
   ```bash
   npm install
   ```

3. **Lancer le serveur de développement local**
   ```bash
   npm run dev
   ```

### Variables d'environnement

Vous devez créer un fichier `.env.local` à la racine du projet et le configurer avec les informations de votre projet Supabase.

| Variable | Description |
| :--- | :--- |
| `VITE_SUPABASE_URL` | L'URL d'API de votre instance Supabase |
| `VITE_SUPABASE_ANON_KEY` | La clé publique (anon) fournie par Supabase |

## 📂 Structure du Projet

Voici un aperçu de l'architecture principale :

```text
fitness-web-app/
├── src/                    # Code source principal
│   ├── assets/             # Fichiers médias statiques (Images)
│   ├── components/         # Composants UI réutilisables (Layout, Boutons, etc.)
│   ├── contexts/           # Gestion globale d'états (ex: Auth)
│   ├── lib/                # Configurations tierces (ex: Client Supabase)
│   ├── pages/              # Vues principales de l'application (Dashboard, etc.)
│   ├── App.jsx             # Configuration des routes
│   └── main.jsx            # Point d'entrée de l'application React
├── supabase/               # Schémas et configurations liés à Supabase
├── public/                 # Fichiers statiques publics
├── .env.local              # Fichier de variables d'environnement (à créer)
├── package.json            # Dépendances du projet et scripts
├── tailwind.config.js      # Configuration de Tailwind
└── vite.config.js          # Configuration du bundler Vite
```

---

## 👨‍💻 À propos du Fondateur

Ce SaaS a été pensé, designé et **développé de A à Z par Kevin Nguena**.

Âgé de 19 ans et actuellement en **première année d'ingénierie informatique à l'EFREI**, je possède une double casquette unique : développeur passionné et expert du milieu sportif. 

En tant que coach en ligne, pratiquant de sports de combat et créateur de contenu fitness (suivi par plus de 100k personnes sur TikTok et 20k sur Instagram), j'ai pu identifier un problème majeur sur le marché : la perte de temps et d'énergie dans la gestion quotidienne des athlètes.

**MACAIRE Coaching** n'est pas qu'un projet étudiant, c'est la résolution technique d'un vrai problème métier. L'objectif de cette V1.0 est d'offrir une plateforme stable, premium et automatisée pour libérer du temps aux coachs, tout en offrant une expérience haut de gamme aux sportifs.

🔗 **Retrouvez-moi sur :**
- [LinkedIn](https://www.linkedin.com/in/kevin-nguena/)
- [Instagram](https://www.instagram.com/kevingym27/)
- [TikTok](https://www.tiktok.com/@kevingym27)
