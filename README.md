# SIKIRA'S FOOD — Site vitrine d'un restaurant

Projet de HOUNGNON Marie-Josée : une page web à but pédagogique présentant le menu d'un restaurant béninois fictif, « SIKIRA'S FOOD ».

## Contenu du site

- **En-tête** : bannière avec logo, menu de navigation (Accueil, Menu, Contact, Paiement) et un slogan.
- **Menu** : deux colonnes de plats traditionnels béninois (riz + haricots, igname pilée + sauce arachide, pâte + sauce gombo, akassa, ablo, gari, etc.), chacun avec photo, description, prix en FCFA et un bouton « acheter ».
- **Pied de page** : présentation du restaurant et liens vers les réseaux sociaux (Twitter, Telegram, Instagram, LinkedIn).

Il s'agit d'une page statique de démonstration : les boutons « acheter » et les liens sociaux ne sont pas fonctionnels.

## Stack technique

- **HTML5** (`index.html`) — structure de la page
- **CSS3** (`style.css`) — mise en page avec Flexbox et media query pour l'adaptation mobile
- Aucune dépendance externe, aucun JavaScript

## Lancer le projet en local

Aucune installation n'est nécessaire. Deux options :

1. **Ouverture directe** : double-cliquer sur `index.html` pour l'ouvrir dans un navigateur.
2. **Serveur local** (recommandé pour un rendu fidèle) :
   ```bash
   npx serve .
   ```
   puis ouvrir l'URL affichée (par défaut http://localhost:3000).

## Remarque

Le fichier `index.html` référence certaines images (`46.jpg`, `9.jpeg`, `2.jpeg`, etc.) qui ne sont pas toutes présentes dans ce dépôt ; seules quelques images (`51.png`, `52.png`, `53.png`, `54.jpg`, captures d'écran) y figurent.
