<div align="center">
<picture>
  <img src="./assets/images/logo/ohmyfood_white.png" alt="Logo Ohmyfood" width="300"/>
  <img src="./assets/images/logo/ohmyfood.png" alt="Logo Ohmyfood" width="300"/>
</picture>

# Ohmyfood

**Projet 4 — OpenClassrooms | Développeur Web**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

---

## Description

**Ohmyfood** est un site de réservation en ligne pour restaurants gastronomiques parisiens.
L'objectif du projet est d'intégrer une maquette mobile-first en HTML/SCSS en respectant scrupuleusement le design Figma fourni.

---

## Aperçu

<picture>
  <img src="./assets/images/logo/ohmyfood_presentation.png" alt="Ohmyfood" height="300"/>
</picture>

---

## Typographie

| Usage         | Police                                                   |
| ------------- | -------------------------------------------------------- |
| Logo & titres | [Shrikhand](https://fonts.google.com/specimen/Shrikhand) |
| Texte courant | [Roboto](https://fonts.google.com/specimen/Roboto)       |

---

## Palette de couleurs

| Nom        | Hex       |
| ---------- | --------- |
| Primary    | `#9356dc` |
| Secondary  | `#ff79da` |
| Tertiary   | `#99e2d0` |
| Badge      | `#008766` |
| Background | `#f6f6f6` |
| Location   | `#eaeaea` |
| Footer     | `#353535` |
| White      | `#ffffff` |
| Icons      | `#7e7e7e` |

---

## Structure du projet

```
Ohmyfood-main/
├── assets/
│   ├── css/
│   │   ├── normalize.css
│   │   └── style.css         ← CSS compilé (ne pas modifier)
│   └── images/
│       ├── logo/
│       └── restaurants/
├── sass/
│   ├── _variables.scss
│   ├── _mixins.scss
│   ├── _body.scss
│   ├── _header.scss
│   ├── _location.scss
│   ├── _hero.scss
│   ├── _function.scss
│   ├── _card.scss
│   ├── _restaurants.scss
│   ├── _footer.scss
│   └── main.scss             ← point d'entrée SCSS
├── index.html
├── package.json
└── README.md
```

---

## Installation

```bash
npm install
```

## Compilation SCSS

Lance le watcher SCSS — il recompile automatiquement à chaque modification :

```bash
npm run sass
```

> Le fichier compilé est généré dans `assets/css/style.css`
