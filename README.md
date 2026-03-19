# ⚡️ MACAIRE Coaching Platform 

> **L'ère des fichiers Excel est révolue.** Ce SaaS a été conçu, développé et déployé de A à Z pour révolutionner le suivi et l'expérience du coaching sportif en ligne. 

*Créé par un étudiant en 1ère année d'ingénierie à l'EFREI et également créateur de contenu fitness, MACAIRE Coaching App est né d'un besoin terrain critique : automatiser la gestion chronophage des athlètes, centraliser les retours hebdomadaires, et offrir une expérience utilisateur haut-de-gamme, digne des meilleurs standards du web privé.*

---

## 🔒 Avertissement (Repository Vitrine)

Ce dépôt GitHub est uniquement un **Showcase technique**. Le code source complet de cette application SaaS (Software as a Service) est strictement privé. 

Cependant, vous pouvez explorer l'application en direct :
🌐 **Lien de Production** : [app.kevingymworkout.com](https://app.kevingymworkout.com)

**Accès Démo Athlète :**
- **Email** : `demo@macaire.com`
- **Mot de passe** : `testeur2026`

---

## 🛠 Stack Technique

Une architecture moderne orientée performance, sécurité et temps réel.

### Frontend
- **React (Vite)** : Rendu ultra-rapide et Hot Module Replacement (HMR).
- **Tailwind CSS** : Intégration d'un système de design sur-mesure, UI premium et totalement responsive.
- **Framer Motion** : Animations fluides, transitions de route et micro-interactions utilisateur.
- **Recharts** : Normalisation et visualisation complexe des données de performance (Data Viz).
- **Lucide React** : Librairie iconographique épurée.

### Backend & BaaS
- **Supabase** : Architecture Serverless robuste.
  - **PostgreSQL** : Base de données relationnelle complexe.
  - **Authentification** : Gestion sécurisée des sessions et jetons (JWT).
  - **Realtime** : Transmission de données via flux WebSockets purs.
  - **Row Level Security (RLS)** : Sécurisation absolue de l'accès aux tables.

### Infrastructure & Déploiement
- **Vercel** : Déploiement continu, CDN global et Serverless Functions.
- **Hostinger** : Gestion DNS et nom de domaine personnalisé sécurisé.

---

## 🚀 Fonctionnalités Clés

### 🛡 Architecture Multi-Rôles Sécurisée
L'application aiguille intelligemment et verrouille l'accès selon les privilèges. Le routage React couplé aux politiques Supabase empêche toute interférence entre les portails.
- **Portail Coach** : Centre de commandement et de gestion globale.
- **Portail Athlète** : Espace d'optimisation personnel.

*[Insérer capture d'écran de la page de connexion sécurisée ici]*

### 📊 Tableau de Bord Athlète
Pensé pour engager l'utilisateur au quotidien.
- **Suivi Nutritionnel Intelligent** : Objectifs caloriques et indicateurs adaptatifs.
- **Check-in Hebdomadaire** : Système conditionnel (verrouillé automatiquement et uniquement disponible le dimanche) pour structurer le feedback.
- **Slider Interactif (Photo)** : Comparaison dynamique Avant/Objectif pour une motivation visuelle concrète.

*[Insérer capture d'écran du Dashboard Athlète ici]*

### 🛠 Espace Coach & Gestionnaire de Programmes
Fini la perte d'informations. Une vue à 360 degrés sur l'équipe.
- **Suivi Panoramique** : Monitoring des check-ins de tous les athlètes en un coup d'œil.
- **Assignation Sur-Mesure** : Création et attribution de programmes d'entraînement modulaires incluant démonstrations vidéos et directives précises.

*[Insérer capture d'écran du Profil Client côté Coach ici]*

### 📈 Analyse de Données & Data Viz
Transformation des datas brutes en indicateurs de performance lisibles.
- **Graphiques d'Évolution (Charges)** : Suivi précis des max et de la surcharge progressive par exercice, avec algorithme de normalisation et traitement des valeurs nulles.
- **Suivi de la Difficulté (RPE)** : Monitoring visuel via `Recharts` pour prévenir le surentraînement ou la sous-estimation de la fatigue.

*[Insérer capture d'écran des Statistiques / Recharts ici]*

### 💬 Messagerie Temps Réel Intégrée
Une communication instantanée pour pallier l'usage de WhatsApp/Messenger.
- **Supabase Realtime** : Synchronisation immédiate des échanges via WebSockets.
- **Système de Notifications Avancé** : Badges dynamiques de messages non lus spécifiques par client, intégrant une logique d'UI professionnelle (formatage `+99` et effacement optimiste synchrone).

*[Insérer capture d'écran de l'interface de Messagerie ici]*

---

## 🔐 Focus Sécurité et Propriété Intellectuelle

L'intégrité des données clients est la priorité de cette architecture :
- **Row Level Security (RLS)** : Implémenté stricto sensu dans la base de données PostgreSQL. Un utilisateur `A` ne peut mathématiquement pas requêter les données, l'entraînement ou les messages d'un utilisateur `B`.
- **Routage Protégé (React Router)** : Guards de composants React vérifiant systématiquement le statut d'authentification et les accès par rôle de l'utilisateur avant le rendu de l'interface.
- **Droits d'Auteur** : Interface propriétaire, copyright protégé MACAIRE 2026.

---

## 📬 Contact & Liens

Ce projet démontre ma capacité à concevoir un produit technique complet, de la base de données jusqu'à l'animation de l'interface web, tout en respectant un besoin business réel.

**Kevin**  
*Lead Developer & Fitness Coach — EFREI Paris (L1)*

- **LinkedIn** : https://www.linkedin.com/in/kevin-nguena/
- **Portail App** : [app.kevingymworkout.com](https://app.kevingymworkout.com)
