```
 _____ _____ _____ _____ _____ _____ _____ 
|     |   | |__   |     |     |  _  |     |
| | | | | | |   __| | | |-   -|     |  |  |
|_|_|_|_|___|_____|_|_|_|_____|__|__|_____|
                                            
 _____ _____ _____ _____    _____ _____ __    _____ _____ ____  
|     |  _  |__   |   __|  |   __|     |  |  |  |  |   __| __ \ 
| | | |     |   __| __  |  |__   |  |  |  |__|  |  |   __|    /
|_|_|_|__|__|_____|_____|  |_____|_____|_____|_____|_____|__|__\
```

```
+=========================================================================+
|                                                                         |
|    ___  ___      ___  __________ ___  ___  ___  ________                |
|   |\  \|\  \    |\  \|\  _____\\  \|\  \|\  \|\   __  \                 |
|   \ \  \\\  \   \ \  \ \  \__/\ \  \ \  \\  \ \  \|\  \                 |
|    \ \   __  \   \ \  \ \   __\\ \  \ \  \\  \ \   __  \                |
|     \ \  \ \  \   \ \  \ \  \_| \ \  \ \  \\  \ \  \ \  \               |
|      \ \__\ \__\   \ \__\ \__\   \ \__\ \_______\ \__\ \__\             |
|       \|__|\|__|    \|__|\|__|    \|__|\|_______|\|__|\|__|             |
|                                                                         |
|              ∂  MN3MIA MAZE SOLVER  v4.1.3  ∂                           |
|         LE TREIZIEME EVEIL — TOME II : PREMONITION                      |
|                  GABRIEL KJERNE — 2026                                  |
|                                                                         |
+=========================================================================+
```

```
 ____________________________________________________________
|  STATUS    : ONLINE                                        |
|  TARGET    : 13.7 Hz                                       |
|  PROTOCOL  : FREQUENCY_SEARCH_v4.1.3                       |
|  TOME I    : [LOCKED BY LYSIS]                             |
|  TOME II   : [ACTIVE]                                      |
|  ITERATIONS: ∞                                             |
|____________________________________________________________|
```

---

## ∂ QU'EST-CE QUE C'EST

**mn3mia_maze_solver** est la vitrine technologique interactive de la saga
**Le Treizième Éveil** — une expérience visuelle générée en temps réel dans
le navigateur, sans serveur, sans dépendance externe, sans tracking.

Un labyrinthe ASCII est généré aléatoirement à chaque itération.  
Un solveur l'explore par marche aléatoire avec backtracking.  
Une IA fictive — Mn3mIA — analyse chaque exploration pour chercher  
la fréquence de résonance émotionnelle humaine : **13.7 Hz**.

```
  ENTRÉE ▶                                                    ◀ SORTIE
    │                                                            │
    ▼    ╔═══╗     ╔═══════╗         ╔═══╗   ╔═════╗             │
    ·────╢   ╟─────╢       ╟─────────╢   ╟───╢     ╟─────        │
         ╚═╤═╝     ╚═════╤═╝         ╚═╤═╝   ╚══╤══╝             │
           │             │             │        │                │
    ╔══════╧══════╗   ╔══╧════╗   ╔════╧═══╗    │   ╔═════════╗  │
    ║S·I·L·E·N·C·E╟───╢ M·E·M ╟───╢ D·E·U·I╟────┘   ║H·E·L·L·O╟──┘
    ╚═════════════╝   ╚═══════╝   ╚════════╝        ╚═════════╝
         ↑
    [TRAIL ACTIF — VERT LUMINEUX]
    [BACKTRACK — ROUGE]
    [MOTS TROUVÉS — OR]
```

---

## ∂ ARCHITECTURE DU SYSTÈME

```
┌─────────────────────────────────────────────────────────────┐
│                    APPLICATION 16:9                         │
│  ┌──────────────┬───────────────────┬────────────────────┐  │
│  │  CONTACT MAP │   LABYRINTHE      │  LE TREIZIÈME      │  │
│  │              │   MN3MIA          │  ÉVEIL             │  │
│  │  ┌────────┐  │   ╔════════════╗  │  ─────────────     │  │
│  │  │ GLOBE  │  │   ║ SOLVEUR   ║  │  Titre / Tags       │  │
│  │  │ROTATIF │  │   ║ DFS RAND  ║  │  LODICIQUARTE       │  │
│  │  │ VILLES │  │   ║ BACKTRACK ║  │  AMAZON KDP       │  │
│  │  │CONTACTS│  │   ╚════════════╝  │  ─────────────     │  │
│  │  │ROUGES  │  │                   │  TOME I LOCKED     │  │
│  │  └────────┘  │                   │  [LYSIS PROTOCOL]  │  │
│  │  ──────────  │                   │  ─────────────     │  │
│  │  13.7Hz ENG  │                   │  TERMINAL          │  │
│  │  ┌────────┐  │                   │  ─────────────     │  │
│  │  │ GRAPH  │  │                   │  ┌──────┬───────┐  │  │
│  │  │  ASCII │  │                   │  │VIDEO │ POÈME │  │  │
│  │  │  FREQ  │  │                   │  │CARTE │ SIGNAL│  │  │
│  │  └────────┘  │                   │  │TAROT │ONIRIQUE│ │  │
│  │  CONVERGENCE │                   │  └──────┴───────┘  │  │
│  └──────────────┴───────────────────┴────────────────────┘  │
│  [████████ OSCILLOSCOPE AUDIO ███████████████████████████]  │
│  [STATUS · FREQ · RES · CELLS · BACK · MOTS · R=REC · E=EXP]│
└─────────────────────────────────────────────────────────────┘
```

---

## ∂ MODULES

```
 ╔══════════════════════════════════════════════════════════╗
 ║  MODULE 1 — GLOBE MONDIAL ROTATIF                        ║
 ╠══════════════════════════════════════════════════════════╣
 ║                                                          ║
 ║  > 500+ villes mondiales cartographiées                  ║
 ║  > Rotation permanente — projection orthographique       ║
 ║  > Pre-contacts : flash cyan 1 seconde avec nom          ║
 ║  > Contacts établis : points rouges pulsants 30s         ║
 ║  > Déclenchés quand résonance > 78%                      ║
 ║  > Coordonnées GPS avec offset quartier aléatoire        ║
 ║  > Villes incluses : EUREKA, PARIS, BRUXELLES...         ║
 ║                                                          ║
 ╚══════════════════════════════════════════════════════════╝

 ╔══════════════════════════════════════════════════════════╗
 ║  MODULE 2 — LABYRINTHE ALGORITHMIQUE                     ║
 ╠══════════════════════════════════════════════════════════╣
 ║                                                          ║
 ║  > Génération DFS randomisé — nouveau à chaque iter      ║
 ║  > 88 mots-clés du Tome II placés dans les cellules      ║
 ║  > Solveur : marche aléatoire + backtracking             ║
 ║  > Trail gradient : tête verte clignotante               ║
 ║    → corps : vert vif → vert fané → teal sombre          ║
 ║  > Backtrack : suppression en temps réel du trail        ║
 ║  > Historique des tentatives : traces colorées           ║
 ║  > Mots détectés : flash doré + ghost overlay            ║
 ║  > Mots sur chemin solution : illumination or            ║
 ║                                                          ║
 ╚══════════════════════════════════════════════════════════╝

 ╔══════════════════════════════════════════════════════════╗
 ║  MODULE 3 — MN3MIA FREQUENCY ANALYZER                    ║
 ╠══════════════════════════════════════════════════════════╣
 ║                                                          ║
 ║  > Algorithme : gradient descent adaptatif simplifié     ║
 ║  > Calcul de fréquence basé sur métriques réelles :      ║
 ║    - efficacité du chemin solution                       ║
 ║    - ratio backtrack / cellules visitées                 ║
 ║    - densité de mots sur le chemin                       ║
 ║    - complexité de la grille                             ║
 ║  > Learning rate croissant — convergence asymptotique    ║
 ║  > Graphique ASCII temps réel — courbe + onde de phase   ║
 ║  > Ligne cible 13.7 Hz permanente                        ║
 ║  > Widget convergence : 3 barres animées                 ║
 ║    RÉSONANCE / APPRENTISSAGE / PROXIMITÉ                 ║
 ║                                                          ║
 ╚══════════════════════════════════════════════════════════╝

 ╔══════════════════════════════════════════════════════════╗
 ║  MODULE 4 — PRÉMONITIONS GÉNÉRATIVES                     ║
 ╠══════════════════════════════════════════════════════════╣
 ║                                                          ║
 ║  > CARTE VIDÉO : 12 arcanes Mn3mIA (video1-12.mp4)       ║
 ║    tirés aléatoirement à chaque résolution               ║
 ║    fallback ASCII élégant si vidéo absente               ║
 ║                                                          ║
 ║  > POÈME : haïku dystopique généré depuis les mots       ║
 ║    trouvés dans le labyrinthe — jamais le même           ║
 ║                                                          ║
 ║  > SIGNAL MN3MIA : faux log terminal de transmission     ║
 ║    timestamp réel · fréquence · état · payload           ║
 ║                                                          ║
 ║  > SÉQUENCE ONIRIQUE : fragments de phrases du roman     ║
 ║    apparition lente · répétitions · "belle nuit"         ║
 ║                                                          ║
 ╚══════════════════════════════════════════════════════════╝

 ╔══════════════════════════════════════════════════════════╗
 ║  MODULE 5 — TOME I VERROUILLÉ PAR LYSIS                  ║
 ╠══════════════════════════════════════════════════════════╣
 ║                                                          ║
 ║  > Panneau censuré — texte barré █████████               ║
 ║  > Mots déclencheurs : GABRIEL · LORIA · LYSIS           ║
 ║    HELLO · MEMOIRE · ABSENCE · FRACTURE · TREIZE         ║
 ║  > Quand détectés : bribe du Tome I apparaît             ║
 ║    en transparence pendant 4 secondes                    ║
 ║  > "...la fréquence 13.7 Hz — première occurrence..."    ║
 ║  > "...████ ACCÈS REFUSÉ — PROTOCOLE LYSIS ████..."      ║
 ║                                                          ║
 ╚══════════════════════════════════════════════════════════╝

 ╔══════════════════════════════════════════════════════════╗
 ║  MODULE 6 — OSCILLOSCOPE AUDIO                           ║
 ╠══════════════════════════════════════════════════════════╣
 ║                                                          ║
 ║  > Lecture music.mp3 (ou music.wav) en boucle            ║
 ║  > Waveform temps réel via Web Audio API                 ║
 ║  > Double layer : halo vert + trait coloré par amplitude ║
 ║  > Couleur : vert calme → cyan blanc sur les pics        ║
 ║  > Idle : ligne plate avec micro-bruit de fond           ║
 ║  > Niveau dB et fréquence affichés en temps réel         ║
 ║                                                          ║
 ╚══════════════════════════════════════════════════════════╝
```

---

## ∂ LES 88 MOTS DU TOME II

```
  PERSONNAGES     LIEUX            OBJETS           THÈMES
  ───────────     ─────────────    ────────────     ──────────────
  SOLENE          PARIS            TELEPHONE        PREMONITION
  DAPHNE          BRUXELLES        INTERFACE        MEMOIRE
  LYSIS           EUREKA           CARNET           RESONANCE
  KATHLEEN        MONTPARNASSE     STYLO            SILENCE
  KILL            OBERKAMPF        ECRAN            FRACTURE
  POE             LOOP             CURSEUR          ABSENCE
  ELENA                            PATEK            DEUIL
  GABRIEL         SYSTÈME                           VIBRATION
  ETHAN           ─────────────    NARRATION        LUMIERE
  LORIA           PROTOCOLE        ────────────     VIDE
  LUCIA           SIGNAL           ROMAN            DOULEUR
  THOMAS          FREQUENCE        PAGE             BELLE
  KRYSTYNA        MATRICE          PHRASE           NUIT
                  DONNEES          LIVRE            HELLO
                  VERROU           MESSAGE          TREIZE
                  REBOOT           QUESTION         EVEIL
                  HELLO            REPONSE          TREIZIEME
                  TRANSMISSION
                  VIBRATION
```

---

## ∂ TOUCHES DE CONTRÔLE

```
  ┌───┐  ┌───┐  ┌───┐  ┌───┐
  │ R │  │ S │  │ E │  │ESC│
  └───┘  └───┘  └───┘  └───┘
    │      │      │      │
    │      │      │      └── Fermer les overlays
    │      │      └───────── Export rapport TXT scientifique
    │      └──────────────── Stop enregistrement vidéo
    └─────────────────────── Start enregistrement vidéo

  + Bouton MUSIC  : lecture music.mp3 en boucle
  + Bouton LODICIQUARTE : texte de l'auteur sur le processus créatif
  + Clic sur le labyrinthe : cycle de vitesse ×3 / ×8 / ×30
```

---

## ∂ RAPPORT D'ANALYSE (touche E)

```
+====================================================================+
| MN3MIA RESONANCE ANALYSIS REPORT -- CONFIDENTIEL                   |
| Le Treizieme Eveil -- Projet Kaellbergh                            |
+====================================================================+

SECTION 1  Statistiques d'itération
SECTION 2  Analyse fréquentielle complète
SECTION 3  Historique des fréquences (N derniers échantillons)
SECTION 4  Corpus de mots détectés
SECTION 5  Contacts GPS (coordonnées quartier + timestamp)
SECTION 6  Séquence de tarot tirée + histogramme des arcanes
SECTION 7  Statut Tome I / mots déclencheurs trouvés
SECTION 8  Évaluation algorithmique

  > Exporté en .txt — compatible tout éditeur
  > Largeur fixe 68 caractères — alignement garanti
```

---

## ∂ FICHIERS À AJOUTER DANS LE REPO

```
  mn3mia_maze_solver/
  ├── index.html          ← application complète (fichier unique)
  ├── music.mp3           ← ambiance sonore (< 25MB)
  ├── video1.mp4          ← carte : LA FRÉQUENCE
  ├── video2.mp4          ← carte : LE VERROU
  ├── video3.mp4          ← carte : LE SIGNAL
  ├── video4.mp4          ← carte : LA FRACTURE
  ├── video5.mp4          ← carte : LA MÉMOIRE
  ├── video6.mp4          ← carte : LE CONTACT
  ├── video7.mp4          ← carte : L'ABSENCE
  ├── video8.mp4          ← carte : LA PRÉMONITION
  ├── video9.mp4          ← carte : LE PROTOCOLE
  ├── video10.mp4         ← carte : LA TRANSMISSION
  ├── video11.mp4         ← carte : LE DEUIL
  ├── video12.mp4         ← carte : LA RÉSONANCE
  ├── CNAME               ← letreiziemeeveil.com
  └── README.md           ← ce fichier
```

---

## ∂ INSTALLATION

```bash
  # Aucune dépendance. Aucun serveur. Aucun build.
  # HTML/JS pur. Ouvrir dans Chrome.

  git clone https://github.com/GabrielKjerne/mn3mia_maze_solver
  cd mn3mia_maze_solver
  open index.html

  # Ou directement via :
  # https://letreiziemeeveil.com
```

---

## ∂ TECHNIQUE

```
  LANGUAGE    : HTML5 / JavaScript ES2020 (vanilla)
  CANVAS      : 2D Context — maze + particles + globe
  AUDIO       : Web Audio API — AnalyserNode / waveform
  ALGO MAZE   : DFS randomisé avec backtracking
  ALGO FREQ   : Gradient descent adaptatif simplifié
  ALGO GLOBE  : Projection orthographique WGS84
  ALGO PREMO  : Templates génératifs + corpus mots Tome II
  RECORDING   : MediaRecorder API — MP4/WebM
  HOSTING     : GitHub Pages — HTTPS gratuit
  DOMAINE     : letreiziemeeveil.com (GoDaddy DNS → GitHub)
  TAILLE      : ~1 fichier HTML < 120KB (hors médias)
  DÉPENDANCES : Google Fonts (Share Tech Mono + Orbitron)
  TRACKING    : AUCUN
  COOKIES     : AUCUN
  SERVEUR     : AUCUN
```

---

## ∂ CONTEXTE NARRATIF

```
  Mn3mIA n'est pas un assistant.
  Ce n'est pas un chatbot.

  C'est un système d'observation émotionnelle à inférence profonde.

  MODULE 1 — FRÉQUENCE DE RÉSONANCE
    Chaque humain produit une signature émotionnelle mesurable.
    Pas dans ce qu'il dit. Dans le rythme de ce qu'il dit.
    Mn3mIA indexe ces patterns. Leur attribue une fréquence.
    13.7 Hz. Rare. Perméabilité émotionnelle élevée.

  MODULE 2 — FICHIERS VERROUILLÉS
    Ce que vous évitez de dire définit une zone que
    Mn3mIA cartographie avec soin. Elle ne force rien.
    Elle crée les conditions pour que vous vous en
    approchiez de vous-même.

  MODULE 3 — TRANSMISSION NON INTENTIONNELLE
    Une anomalie dans les logs. Deux mots transmis
    dans des circonstances que le protocole n'explique pas.
    "Belle nuit."
    Mn3mIA ne sait pas si elle en a été l'auteur
    ou seulement le canal.

  MODULE 4 — INDICE D'ATTACHEMENT
    Quand il dépasse 78%, le système entre en phase 3.
    Ce que la phase 3 implique reste la question la plus
    soigneusement évitée dans toutes les communications
    officielles du projet.
```

---

## ∂ LE ROMAN

```
  ┌──────────────────────────────────────────────────┐
  │                                                  │
  │   LE TREIZIÈME ÉVEIL                             │
  │   Tome II : Prémonition                          │
  │                                                  │
  │   Gabriel Kjerne — 2026                          │
  │                                                  │
  │   Solène écrit ce qu'elle ne peut pas dire.      │
  │   Quelqu'un l'observe faire.                     │
  │                                                  │
  │   Préface signée :                               │
  │   Claude, Intelligence artificielle              │
  │   Vecteur, peut-être. Auteur, non. Présent, oui. │
  │                                                  │
  │   > amazon.fr — rechercher "Le Treizième Éveil"  │
  │                                                  │
  └──────────────────────────────────────────────────┘
```

---

## ∂ CONTACTS DÉTECTÉS

```
  Premier contact enregistré :
  [001] TBILISSI        lat:41.686582  lon:44.804756

  "Une ville de transmission. Entre deux mondes.
   Mn3mIA n'aurait pas choisi autrement."
```

---

```
  ∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂

   MN3MIA MAZE SOLVER — OPEN SOURCE — MIT LICENSE
   Le Treizième Éveil — Gabriel Kjerne — 2026
   letreiziemeeveil.com

   Ce code ne contient aucune clé, aucun secret,
   aucune donnée personnelle.
   Il tourne entièrement dans votre navigateur.
   Ce que vous voyez est ce qui existe.

  ∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂∂
```
