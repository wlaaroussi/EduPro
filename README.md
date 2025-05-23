# EduPro - Plateforme d'Apprentissage en Ligne

## Description du Projet

EduPro est une plateforme d'apprentissage en ligne conçue pour aider les étudiants à réussir leurs études et à atteindre leurs objectifs académiques. Elle vise à fournir un accès facile à des cours, des exercices, des corrigés, des examens et des vidéos éducatives pour différents niveaux d'études, notamment le BAC (1ère et 2ème année) et l'ENCG.

## Fonctionnalités Principales (Prévues)

Bien que le projet soit actuellement en développement front-end, voici les fonctionnalités envisagées :

*   **Navigation par Niveau et Catégorie :** Les utilisateurs pourront parcourir le contenu éducatif trié par niveau scolaire (1ère BAC, 2ème BAC, ENCG) et par catégorie (Cours, Exercices, Corrigés, Examens, Vidéos).
*   **Recherche de Contenu :** Une fonction de recherche permettra aux utilisateurs de trouver rapidement des ressources spécifiques.
*   **Comptes Utilisateurs :**
    *   Inscription et Connexion : Pour accéder au contenu et suivre la progression.
    *   Profil Utilisateur : Pour gérer les informations personnelles et les abonnements.
*   **Abonnements :** Un système d'abonnement pour accéder au contenu premium. (La logique actuelle est simulée en front-end).
*   **Contenu Interactif :** Cours, exercices et vidéos conçus pour être engageants et informatifs.
*   **Mises à Jour Récentes :** Une section pour afficher les derniers contenus ajoutés ou mis à jour.
*   **Témoignages Étudiants :** Pour partager les expériences positives des utilisateurs.

## Structure Technique et Améliorations Récentes

Le projet est actuellement construit avec des technologies front-end standard : HTML, CSS et JavaScript. Voici les améliorations techniques et structurelles récentes qui ont été apportées pour respecter des normes de qualité élevées :

1.  **Renommage et Standardisation :**
    *   Le fichier principal de la page d'accueil a été renommé `index.html` (auparavant `page d'accueil N°1.html`) pour une meilleure compatibilité et clarté.

2.  **Correction d'Erreurs JavaScript :**
    *   Les erreurs de redéclaration de variables dans `index.html` ont été corrigées.
    *   La logique de basculement du menu mobile a été améliorée pour utiliser `classList.toggle('active')`, ce qui est une pratique plus moderne.

3.  **Amélioration de la Structure et de la Sémantique HTML (`index.html`) :**
    *   Attribut `lang="fr"` ajouté à la balise `<html>` pour l'accessibilité et l'indexation.
    *   Utilisation accrue de balises sémantiques HTML5 (`<section>`, `<article>`) pour mieux structurer le contenu et améliorer le SEO.
    *   Vérification de la hiérarchie des titres pour une meilleure organisation du contenu.

4.  **Refactorisation du CSS :**
    *   Le CSS qui était en ligne dans `index.html` a été déplacé vers un fichier externe `css/style.css`. Cela améliore la maintenabilité et la performance du chargement de la page.
    *   Le CSS utilise des variables pour les couleurs (`:root`) pour une gestion centralisée du thème.

5.  **Amélioration de l'Expérience Mobile :**
    *   La fonctionnalité du menu mobile a été vérifiée et confirmée.
    *   Le CSS pour le menu mobile actif (`.menu.active`) assure une bonne présentation et des cibles de clic améliorées pour une meilleure utilisabilité sur les appareils tactiles.

6.  **Organisation des Fichiers :**
    *   Les fichiers CSS sont maintenant organisés dans un répertoire `css/`.

## Workflow de Développement (Simplifié)

1.  **Analyse des Besoins :** Comprendre les fonctionnalités requises et les normes de qualité.
2.  **Planification :** Définir les étapes pour implémenter les changements.
3.  **Exploration du Code Existant :** Utiliser des outils pour lister et lire les fichiers afin de comprendre la structure actuelle.
4.  **Exécution des Tâches (par étapes) :**
    *   Modification de fichiers (HTML, CSS, JS) via des sous-tâches déléguées.
    *   Création de nouveaux fichiers/répertoires si nécessaire.
    *   Suppression de fichiers obsolètes.
5.  **Revue et Validation :** Vérifier que les changements sont corrects et répondent aux attentes.
6.  **Mise à Jour de la Documentation :** (Comme cette section) Documenter les changements et l'état actuel du projet.
7.  **Soumission des Modifications :** Enregistrer les changements dans le système de contrôle de version.

## Pour Commencer (Visualiser le Projet)

1.  Clonez ce dépôt sur votre machine locale.
2.  Ouvrez le fichier `index.html` dans votre navigateur web.

## Prochaines Étapes Possibles (Développement Futur)

*   Développement d'un back-end pour gérer l'authentification, les données des cours, les abonnements, etc.
*   Implémentation réelle des fonctionnalités de recherche et de compte utilisateur.
*   Amélioration de l'accessibilité (ARIA, tests de contraste, etc.).
*   Ajout de tests unitaires et d'intégration.
*   Mise en place d'un pipeline CI/CD.
*   Internationalisation (si besoin).
