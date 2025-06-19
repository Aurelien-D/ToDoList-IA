# TodoList IA - Refonte 2025

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)

Une application web de gestion de tâches intelligente et moderne, conçue pour optimiser la productivité grâce à une interface soignée et des fonctionnalités assistées par l'Intelligence Artificielle.

**[➡️ Accéder à la Démo Live]()**

## 🚀 À propos du projet

Ce projet est une réinterprétation ambitieuse de la "To-Do List" classique. L'objectif était de créer une expérience utilisateur complète, intégrant non seulement les fonctionnalités de base d'un gestionnaire de tâches, mais aussi des outils avancés comme un tableau de bord analytique, des alertes intelligentes et un assistant IA, le tout dans une interface responsive et agréable à utiliser.

L'application est développée en **JavaScript pur (Vanilla JS)**, en utilisant une approche orientée objet pour garantir un code structuré, maintenable et scalable.

## ✨ Fonctionnalités Clés

### Gestion de Tâches Avancée
- [cite_start]**Système Kanban :** Organisez vos tâches dans trois colonnes : "À faire", "En cours" et "Terminé".
- [cite_start]**Drag & Drop :** Déplacez intuitivement les tâches entre les colonnes.
- [cite_start]**Détails Complets :** Ajoutez des titres, des dates/heures d'échéance, des catégories et des niveaux de priorité (Basse, Normale, Haute, Critique).
- **Sous-tâches :** Décomposez des tâches complexes en étapes plus simples. [cite_start]Créez une sous-tâche en glissant une tâche sur une autre!
- [cite_start]**Alertes d'Échéance :** Recevez des notifications pour les tâches en retard ou arrivant à échéance.

### 🤖 Assistant IA & Fonctionnalités Intelligentes
- [cite_start]**Génération de Sous-tâches :** Laissez l'IA analyser une tâche et proposer une liste de sous-tâches pertinentes.
- [cite_start]**Catégorisation Automatique :** L'IA analyse le titre de votre tâche pour lui assigner la catégorie la plus logique.
- [cite_start]**Suggestion de Priorité :** Le système suggère une priorité en fonction des mots-clés détectés dans le titre (urgent, asap, etc.).
- [cite_start]**Dictée Vocale :** Ajoutez des tâches rapidement en utilisant votre voix, avec reconnaissance de commandes simples ("ajouter tâche", "mode sombre", etc.).

### 📊 UI/UX & Productivité
- [cite_start]**Tableau de Bord Analytique :** Visualisez votre productivité avec un taux de complétion, des compteurs de tâches et des statistiques par catégorie.
- [cite_start]**Thème Sombre & Clair :** Basculez entre deux thèmes pour un confort visuel optimal.
- [cite_start]**Recherche Instantanée :** Retrouvez n'importe quelle tâche grâce à une barre de recherche rapide (avec debounce pour la performance).
- [cite_start]**Notifications :** Un système de notifications non-bloquant pour informer des succès, erreurs ou actions (avec une option "Annuler" pour les suppressions).
- [cite_start]**Raccourcis Clavier :** Accédez aux fonctions clés (nouvelle tâche, recherche, thème, etc.) pour une navigation plus rapide.
- [cite_start]**Persistance des Données :** Toutes vos tâches et préférences sont sauvegardées localement dans votre navigateur (`localStorage`).
- **100% Responsive :** L'interface s'adapte parfaitement aux ordinateurs, tablettes et mobiles.

## 🛠️ Technologies Utilisées

- **Front-End :**
  - [cite_start]HTML5 
  - [cite_start]CSS3 (avec variables, Flexbox, Grid, et une approche "glassmorphism") 
  - [cite_start]JavaScript (ES6+, approche orientée objet avec des classes) 
- **Back-End (pour l'IA) :**
  - [cite_start]L'application est conçue pour communiquer avec un endpoint backend (déployé sur Render) qui relaie les requêtes vers une API d'IA.

## ⚙️ Installation et Lancement Local

Ce projet ne nécessite aucune étape de compilation.

1.  Clonez le dépôt :
    ```sh
    git clone 
    ```
2.  Naviguez dans le dossier du projet :
    ```sh
    cd todolist
    ```
3.  Ouvrez le fichier `index.html` directement dans votre navigateur.

## 👨‍💻 Auteur

- **Aurélien DUJEUX** - [Aurelien-D sur GitHub](https://github.com/Aurelien-D)