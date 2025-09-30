[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VOTRE_NOM/NOM_DU_REPO/blob/main/VOTRE_FICHIER.ipynb)
# 🎮 Sudoku Interactif pour Google Colab

Ce projet est une implémentation complète d'un **jeu de Sudoku interactif** en Python, conçu spécifiquement pour être exécuté dans un environnement **Google Colab** ou **Jupyter Notebook**.

Il utilise la bibliothèque **`ipywidgets`** pour créer une interface utilisateur graphique (GUI) directement dans le notebook, permettant aux joueurs de cliquer sur les cases et les chiffres.

## ✨ Fonctionnalités

* **Génération de Grilles :** Crée des puzzles de Sudoku jouables avec des niveaux de difficulté ajustables (Facile, Moyen, Difficile).
* **Résolution par Backtracking :** Inclut un algorithme de résolution pour garantir la validité des puzzles et afficher la solution sur demande.
* **Interface Réactive :** Utilisation des boutons (`ipywidgets.Button`) pour la grille, les chiffres et les contrôles.
* **Feedback Visuel :** Mise en évidence de la cellule sélectionnée et affichage des erreurs immédiates (case rouge) lors de l'entrée d'un chiffre incorrect.

## 🚀 Comment Lancer le Jeu

1.  **Ouvrez ce fichier** (ou le fichier `.py` / `.ipynb`) dans Google Colab.
2.  Exécutez la cellule de code contenant la fonction `play_sudoku()`.

Le jeu se lancera immédiatement, affichant la grille interactive.
