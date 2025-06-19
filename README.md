# TodoList IA

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)

Une application web de gestion de tâches intelligente et moderne, conçue pour optimiser la productivité grâce à une interface soignée et des fonctionnalités assistées par l'Intelligence Artificielle.

**[➡️ Accéder à la Démo Live](https://aurelien-d.github.io/ToDoList-IA/)**

## 🚀 À propos du projet

Ce projet est une réinterprétation ambitieuse de la "To-Do List" classique. L'objectif était de créer une expérience utilisateur complète, intégrant non seulement les fonctionnalités de base d'un gestionnaire de tâches, mais aussi des outils avancés comme un tableau de bord analytique, des alertes intelligentes et un assistant IA, le tout dans une interface responsive et agréable à utiliser.

L'application est développée en **JavaScript pur (Vanilla JS)**, en utilisant une approche orientée objet pour garantir un code structuré, maintenable et scalable. Elle communique avec un **backend Node.js dédié** pour les fonctionnalités IA.

## ✨ Fonctionnalités Clés

### Gestion de Tâches Avancée
- **Système Kanban :** Organisez vos tâches dans trois colonnes : "À faire", "En cours" et "Terminé".
- **Drag & Drop :** Déplacez intuitivement les tâches entre les colonnes.
- **Détails Complets :** Ajoutez des titres, des dates/heures d'échéance, des catégories et des niveaux de priorité (Basse, Normale, Haute, Critique).
- **Sous-tâches :** Décomposez des tâches complexes en étapes plus simples. Créez une sous-tâche en glissant une tâche sur une autre !
- **Alertes d'Échéance :** Recevez des notifications pour les tâches en retard ou arrivant à échéance.

### 🤖 Assistant IA & Fonctionnalités Intelligentes
- **Génération de Sous-tâches :** Laissez l'IA analyser une tâche et proposer une liste de sous-tâches pertinentes.
- **Catégorisation Automatique :** L'IA analyse le titre de votre tâche pour lui assigner la catégorie la plus logique.
- **Suggestion de Priorité :** Le système suggère une priorité en fonction des mots-clés détectés dans le titre (urgent, asap, etc.).
- **Dictée Vocale :** Ajoutez des tâches rapidement en utilisant votre voix, avec reconnaissance de commandes simples ("ajouter tâche", "mode sombre", etc.).

### 📊 UI/UX & Productivité
- **Tableau de Bord Analytique :** Visualisez votre productivité avec un taux de complétion, des compteurs de tâches et des statistiques par catégorie.
- **Thème Sombre & Clair :** Basculez entre deux thèmes pour un confort visuel optimal.
- **Recherche Instantanée :** Retrouvez n'importe quelle tâche grâce à une barre de recherche rapide.
- **Notifications :** Un système de notifications non-bloquant pour informer des succès, erreurs ou actions (avec une option "Annuler" pour les suppressions).
- **Raccourcis Clavier :** Accédez aux fonctions clés pour une navigation plus rapide.
- **Persistance des Données :** Toutes vos tâches et préférences sont sauvegardées localement dans votre navigateur (`localStorage`).
- **100% Responsive :** L'interface s'adapte parfaitement aux ordinateurs, tablettes et mobiles.

## 🛠️ Technologies Utilisées

- **Front-End :**
  - HTML5
  - CSS3 (avec variables, Flexbox, Grid, et une approche "glassmorphism")
  - JavaScript (ES6+, approche orientée objet avec des classes)
- **Back-End (pour l'IA) :**
  - Le front-end communique avec un **[Backend Node.js dédié](https://github.com/Aurelien-D/ToDoList-IA-BackEnd)** qui sert de proxy sécurisé vers l'API d'OpenAI.

## ⚙️ Lancement Local

Ce projet ne nécessite aucune étape de compilation.

1.  Clonez le dépôt :
    ```sh
    git clone [https://github.com/Aurelien-D/ToDoList-IA.git](https://github.com/Aurelien-D/ToDoList-IA.git)
    ```
2.  Naviguez dans le dossier du projet :
    ```sh
    cd ToDoList-IA
    ```
3.  Ouvrez le fichier `index.html` directement dans votre navigateur.

## 👨‍💻 Auteur

- **Aurélien DUJEUX** - [Aurelien-D sur GitHub](https://github.com/Aurelien-D)