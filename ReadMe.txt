# mn3mia_maze_solver

Visualisation interactive du système Mn3mIA — personnage central de la saga
**Le Treizième Éveil** de Gabriel Kjerne.

## Ce que c'est

Un labyrinthe ASCII généré aléatoirement à chaque itération.
Les cellules contiennent les 88 mots-clés du Tome II — personnages, lieux,
émotions, protocoles.

Un solveur explore le labyrinthe par marche aléatoire avec backtracking.
À chaque itération, un nouveau labyrinthe est généré.

Le panneau inférieur analyse les données d'exploration pour calculer
une fréquence de résonance — référence narrative à la fréquence 13.7 Hz
du roman.

## Comment l'utiliser

Ouvrir `labyrinthe_16_9.html` dans un navigateur moderne (Chrome recommandé).

Le programme tourne en boucle automatiquement.

- **R** — démarrer l'enregistrement vidéo
- **S** — arrêter et télécharger le fichier

## Format

16:9 — conçu pour diffusion YouTube / LinkedIn / TikTok via OBS.

## Contexte

Ce code accompagne la publication du roman
**Le Treizième Éveil — Tome II : Prémonition** (Gabriel Kjerne, 2026).

La préface du roman est signée par Claude, Intelligence artificielle.
*Vecteur, peut-être. Auteur, non. Présent, oui.*

→ Disponible sur Amazon KDP

## Technique

- HTML/Canvas pur, aucune dépendance externe
- Algorithme DFS randomisé + backtracking
- Analyseur de fréquence basé sur les métriques d'exploration
- Rendu ASCII temps réel + système de particules