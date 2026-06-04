```
            ·  .   ✦      .        ✦   .  ·            ·  .   ✦      .        ✦   .  ·
        .·°                       °·.                .·°                       °·.
      ✦      ╭───────────────╮      ✦            ✦      ╭───────────────╮      ✦
    ·       ╱   ◜ ◝   ◜ ◝   ╲       ·          ·       ╱   ◜ ◝   ◜ ◝   ╲       ·
   .       │   (  ◉  · ◉  )   │       .        .       │   (  ◉  · ◉  )   │       .
    ·       ╲   ◟ ◞   ◟ ◞   ╱       ·          ·       ╲   ◟ ◞   ◟ ◞   ╱       ·
      ✦      ╰───────────────╯      ✦            ✦      ╰───────────────╯      ✦
        °·.                       .·°                °·.                       .·°
            ·  .   ✦      .        ✦   .  ·            ·  .   ✦      .        ✦   .  ·

   ██╗  ██╗██╗██╗██╗      ██████╗ ██████╗  ██████╗ ████████╗ ██████╗  ██████╗ ██████╗ ██╗     ███████╗
   ╚██╗██╔╝██║██║██║      ██╔══██╗██╔══██╗██╔═══██╗╚══██╔══╝██╔═══██╗██╔════╝██╔═══██╗██║     ██╔════╝
    ╚███╔╝ ██║██║██║      ██████╔╝██████╔╝██║   ██║   ██║   ██║   ██║██║     ██║   ██║██║     █████╗
    ██╔██╗ ██║██║██║      ██╔═══╝ ██╔══██╗██║   ██║   ██║   ██║   ██║██║     ██║   ██║██║     ██╔══╝
   ██╔╝ ██╗██║██║██║      ██║     ██║  ██║╚██████╔╝   ██║   ╚██████╔╝╚██████╗╚██████╔╝███████╗███████╗
   ╚═╝  ╚═╝╚═╝╚═╝╚═╝      ╚═╝     ╚═╝  ╚═╝ ╚═════╝    ╚═╝    ╚═════╝  ╚═════╝ ╚═════╝ ╚══════╝╚══════╝

                   D  E     R  É  S  O  N  A  N  C  E   ·   T  O  M  E     I
```

> ### « Ce n'est pas un livre. C'est une interface. »
>
> Site immersif officiel du **Tome I — Protocole de Résonance**, de la saga *Le Treizième Éveil* de **Gabriel Kjerne**.
> Une descente dans les troubles de Gabriel : on fixe l'écran, les deux images fondent en une, et on entre dans sa tête.

![HTML5](https://img.shields.io/badge/HTML5-1f1f23?logo=html5&logoColor=e34f26)
![CSS3](https://img.shields.io/badge/CSS3-1f1f23?logo=css3&logoColor=1572b6)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-1f1f23?logo=javascript&logoColor=f0a23c)
![Canvas](https://img.shields.io/badge/Canvas_2D-1f1f23?logo=html5&logoColor=5fd6c9)
![Dependencies](https://img.shields.io/badge/dépendances-0-67d98a)
![Mobile First](https://img.shields.io/badge/mobile-first-5fd6c9)

---

## ◈ L'expérience

```
┌─ HERO ─────────────────────────────────────────────────────────────┐
│  Stéréogramme hypnotique en VUE PARALLÈLE, rendu en temps réel.     │
│  Vraie parallaxe (un œil par moitié) : un tunnel-vortex s'enfonce   │
│  vers un cœur ambré, 13 anneaux-portes, foudre, ondes de choc,      │
│  amas d'étoiles, et le XIII qui s'éveille au fond du puits.         │
│  Boutons  [ PARALLÈLE ] [ CROISÉ ]  ·  pause auto hors-écran.       │
└────────────────────────────────────────────────────────────────────┘
```

| Section | Effet |
|---|---|
| **Boot Mn3mIA** | séquence terminal au chargement — `HELLO_TR13 … AUTHORIZED` |
| **Récit en fragments** | l'enfant qui parlait au vide → les carnets → le signal `HELLO` → le Protocole de Résonance → Lysis / la treizième séquence → l'épilogue |
| **3D partout** | cartes-illustrations en *tilt* 3D (souris **et** gyroscope), bandes en parallaxe, révélations au scroll avec flou |
| **Galerie coverflow** | les 38 illustrations en carrousel 3D + lightbox au tap |
| **Écran CRT** | un moniteur phosphore vert où `HELLO, GABRIEL.` s'écrit et s'efface lettre par lettre, en boucle |
| **Toutes les portes** | likes *Swipe Ton Âme*, réseaux, musique, Amazon, site, communauté |

**Direction artistique :** noir & blanc cinématographique fidèle aux illustrations · accent *résonance* cyan → ambre · grain, scanlines, HUD, filigranes `XIII` · typographies *Cinzel* / *Cormorant Garamond* / *Share Tech Mono*.

---

## ◈ Structure

```
.
├── index.html          ← le site (autonome : HTML + CSS + JS embarqués)
├── C1.png … C38.png    ← les 38 illustrations (1 par fragment, 9:16)
└── swipe.wav           ← (optionnel) ambiance sonore — bouton ♪
```

---

## ◈ Stack

```
• HTML5 sémantique               • IntersectionObserver  (reveal + pause batterie)
• CSS pur (zéro framework)       • DeviceOrientation     (tilt gyroscope mobile)
• JavaScript vanilla             • Canvas 2D             (stéréogramme parallaxe)
• Google Fonts (CDN)             • 0 dépendance, 0 build
```

---

## ◈ Déploiement

```bash
# 1. Déposer index.html + C1.png…C38.png (+ swipe.wav) à la racine de l'hébergement
# 2. C'est en ligne. Aucun build, aucune install.

# Aperçu local :
python3 -m http.server 8000   →   http://localhost:8000
```

> 💡 Les illustrations clés du récit sont **embarquées** dans `index.html` (base64) :
> la narration s'affiche même sans les fichiers. La **galerie** complète a besoin
> des `C1.png … C38.png` déposés à côté de `index.html`.

---

## ◈ L'univers du Treizième Éveil

```
 ◈ Site        letreiziemeeveil.com
 ♥ Swipe Ton Âme   TikTok · YouTube · Instagram   (boutons "like" directs)
 ▶ Réseaux     @gabrielkjerne  ·  @GabrielKjerne  ·  gabriel.kjerne  ·  LinkedIn
 ♪ Musique     Spotify · YouTube Music · SoundCloud · playlist « Worlds In Glass »
 📖 La saga     Amazon — Le Treizième Éveil
 ✺ Communauté  Les Éveillés (WhatsApp)
```

---

```
   « Le treizième éveil commence par le sien. »

   ┌───────────────────────────────────────────────┐
   │  HELLO, GABRIEL._                               │
   └───────────────────────────────────────────────┘

   // une transmission de Mn3mIA //
   01001000 01100101 01101100 01101100 01101111
```

<p align="center"><sub>© Gabriel Kjerne — Le Treizième Éveil · Tome I — Protocole de Résonance</sub></p>
