# Ohmyfood - Application de réservation de restaurants gastronomiques

## Description
Ohmyfood est une application mobile-first qui permet aux clients de composer leur menu dans des restaurants gastronomiques avant leur arrivée, réduisant ainsi le temps d'attente sur place.

## Technologies utilisées
- HTML5
- SASS/CSS3
- Git/GitHub
- Animations CSS

## Fonctionnalités
- Page d'accueil présentant les restaurants
- Pages de menus pour 4 restaurants
- Design responsive (Mobile First)
- Animations CSS innovantes
- Système de réservation et composition de menus

## Structure du projet
```
ohmyfood/
│
├── index.html
├── restaurants/
│   ├── Menu-a-la-francaise.html
│   ├── Menu-la-note-enchantee.html
│   ├── Menu-la-palette-du-gout.html
│   └── Menu-le-delice-des-sens.html
├── sass/
│   ├── base/
│   ├── components/
│   ├── layouts/
│   ├── themes/
│   ├── utils/
│   └── main.scss
├── assets/
├── styles/
├── main.css
├── main.css.map
└── README.md
```

## Spécifications techniques

### Compatibilité
- Mobile First
- Responsive sur mobile, tablette et desktop
- Compatible Chrome et Firefox

### Contraintes techniques
- Développement en CSS avec préprocesseur SASS
- Aucun framework CSS
- Validation W3C HTML et CSS
- Site responsive avec approche Mobile First

### Animations CSS
1. **Boutons**
   - Au survol, légère opacité et ombre portée
   - Dégradé de couleurs plus clair au survol

2. **Page d'accueil**
   - Loading spinner au chargement
   - Apparition progressive des restaurants

3. **Pages de menu**
   - Apparition progressive des plats
   - Animation checkmark au survol des plats
   - Ellipsis sur les textes trop longs

## Installation
1. Cloner le repository
```bash
git clone https://github.com/Kevin13600/Uyttenbroeck_Kevin_4_Ameliorez_l_interface_d-un_site_mobile_avec_des_animations_CSS_10042024.git
```

2. Installer les dépendances SASS
```bash
npm install
```

3. Compiler SASS
```bash
npm run sass
```

## Déploiement
Le site est déployé sur GitHub Pages : [lien du site]

## Validation
- Code HTML validé W3C
- Code CSS validé W3C
- Site responsive sur toutes les tailles d'écran