<div align="center">
  <img src="./assets/images/logo/ohmyfood.png" alt="Logo Ohmyfood" width="200"/>

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

> 🔗 [Voir le site de référence](https://ohmyfood.mathisbarre.com/)

---

## Typographie

| Usage | Police |
|---|---|
| Logo & titres | [Shrikhand](https://fonts.google.com/specimen/Shrikhand) |
| Texte courant | [Roboto](https://fonts.google.com/specimen/Roboto) |

---

## Palette de couleurs

| Nom | Couleur | Hex |
|---|---|---|
| Primary | ![#9356dc](https://via.placeholder.com/15/9356dc/9356dc.png) | `#9356dc` |
| Secondary | ![#ff79da](https://via.placeholder.com/15/ff79da/ff79da.png) | `#ff79da` |
| Tertiary | ![#99e2d0](https://via.placeholder.com/15/99e2d0/99e2d0.png) | `#99e2d0` |
| Badge | ![#008766](https://via.placeholder.com/15/008766/008766.png) | `#008766` |
| Background | ![#f6f6f6](https://via.placeholder.com/15/f6f6f6/f6f6f6.png) | `#f6f6f6` |
| Location | ![#eaeaea](https://via.placeholder.com/15/eaeaea/eaeaea.png) | `#eaeaea` |
| Footer | ![#353535](https://via.placeholder.com/15/353535/353535.png) | `#353535` |
| White | ![#ffffff](https://via.placeholder.com/15/ffffff/ffffff.png) | `#ffffff` |
| Icons | ![#7e7e7e](https://via.placeholder.com/15/7e7e7e/7e7e7e.png) | `#7e7e7e` |

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
