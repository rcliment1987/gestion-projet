# 🏗️ BIMsmarter - Suivi de Projet

Application de suivi de projet avec assistant IA, conçue pour les coordinateurs BIM et chefs de projet.

![BIMsmarter](https://bimsmarter.eu/wp-content/uploads/2024/07/BIM_Smarter_logo.jpg)

## ✨ Fonctionnalités

### 📊 Dashboard
- Statistiques en temps réel (tâches totales, terminées, en cours, à faire)
- Barre de progression globale
- Graphiques interactifs (répartition par statut et priorité)
- Fil d'activité récente

### ✅ Gestion des Tâches
- Création, modification, suppression de tâches
- **Sous-tâches** : hiérarchie à 2 niveaux
- Catégories : Développement, Design, Réunion, Revue, Autre
- Priorités : Haute, Moyenne, Basse
- Statuts : À faire, En cours, Terminé
- Filtres et recherche instantanée

### 📅 Calendrier
- Vue mensuelle interactive
- Visualisation des tâches par date d'échéance
- Navigation mois par mois
- Création rapide de tâches au clic

### 🔗 Synchronisation Calendrier
- Export au format iCal (.ics)
- Intégration Google Calendar
- Intégration Outlook Calendar

### 🤖 Assistant IA (Mistral)
- Chatbot intégré propulsé par Mistral AI
- Contexte automatique des tâches
- Conseils de productivité
- Actions rapides prédéfinies

## 🚀 Installation

### Option 1 : Fichier unique (recommandé)
1. Téléchargez `index.html`
2. Ouvrez-le dans votre navigateur
3. C'est tout ! ✅

### Option 2 : Hébergement web
1. Uploadez `index.html` sur votre hébergeur (Hostinger, Netlify, etc.)
2. Configurez votre sous-domaine

## 🎨 Design

- **Thème BIMsmarter** : Fond sombre (#0f172a) avec accents cyan
- **Pattern** : Points cyan subtils en arrière-plan
- **Glass panels** : Effet glassmorphism moderne
- **Responsive** : Adapté mobile, tablette et desktop

## 💾 Stockage des données

Les données sont stockées localement dans votre navigateur (localStorage) :
- `bimsmarter_tasks` : Liste des tâches
- `bimsmarter_activities` : Historique des activités

## 🔑 Configuration API Mistral

L'API Mistral est pré-configurée. Pour utiliser votre propre clé :
1. Obtenez une clé sur [console.mistral.ai](https://console.mistral.ai)
2. Remplacez `MISTRAL_API_KEY` dans le code

## 📱 Responsive Design

| Appareil | Résolution | Support |
|----------|------------|---------|
| Mobile | < 480px | ✅ |
| Tablette | 480-1024px | ✅ |
| Desktop | > 1024px | ✅ |

## 🛠️ Technologies

- HTML5 / CSS3 / JavaScript (Vanilla)
- Chart.js pour les graphiques
- API Mistral AI pour le chatbot
- LocalStorage pour la persistance

## 📄 Licence

MIT License - BIMsmarter © 2026

## 🔗 Liens

- [BIMsmarter.eu](https://bimsmarter.eu)
- [Documentation](https://bimsmarter.eu/docs)





A RAJOUTER :
ATTRIBUTION DES PERSONNES (via base de données firebase)
ATTRIBUTION DES ROLES DES PERSONNES
Pouvoir envoyer chaque tâches individuellements dans un calendrier google ou outlook.
Pouvoir envoyer toutes les tâches d'une personne dans son calendrier outlook ou google.
Prévoir l'export en EXCEL ou PDF plutôt qu'en JSON
