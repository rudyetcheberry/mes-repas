# 🏠 Maison & Repas

PWA (application web installable) pour organiser les repas de la maison : **menus de la semaine, liste de courses et budget**, alimentée par la saisie des tickets de caisse. Un seul écran, aucune dépendance, fonctionne hors ligne.

## 📱 Installation sur smartphone

1. Ouvrez l'adresse de l'application (GitHub Pages) dans Chrome/Safari
2. **Android (Chrome)** : menu ⋮ → « Ajouter à l'écran d'accueil »
3. **iPhone (Safari)** : bouton Partager → « Sur l'écran d'accueil »

L'application s'ouvre alors comme une vraie appli, plein écran, même sans internet.

## 🚀 Ouverture sur ordinateur

Ouvrez directement l'URL de l'application, ou téléchargez `index.html` et double-cliquez dessus (fonctionne aussi en fichier local, sans installation).

## 📅 Menus

- Planning hebdomadaire : 7 jours × midi/soir, navigation semaine par semaine
- Bouton « Proposer un menu » : remplit la semaine à partir de vos recettes
- 8 recettes familiales pré-chargées (pour 4 personnes), modifiables et complétables avec vos propres recettes (ingrédients + quantités)

## 🛒 Courses

- **Génération automatique de la liste** depuis les recettes du menu (quantités ajustées pour 4 personnes, ingrédients agrégés)
- Liste organisée par rayon (8 catégories), cases à cocher, ajout manuel, impression, copie
- Conseils anti-gaspillage et routines de courses intégrés

## 💰 Budget

- **⚡ Ticket express** : date + magasin + total, c'est tout — le budget se met à jour en 10 secondes (sans détail par rayon)
- **📷 Photo du ticket intégrée** : photographiez le ticket depuis l'application, l'OCR intégré lit les lignes « nom … prix » et remplit le ticket automatiquement (première utilisation : téléchargement du module de lecture, connexion requise une fois)
- **Collage de texte** : alternative via Google Lens (photo → copier le texte → coller) ; les lignes TOTAL / TVA / ESPÈCES sont ignorées
- **Saisie détaillée** : article, catégorie (devinée automatiquement), quantité, prix
- Tableau de bord : dépenses du mois, panier moyen, dépense hebdomadaire moyenne, répartition par catégorie, évolution sur 6 mois
- Suivi vs objectif mensuel + historique ; l'objectif peut être défini après 1-2 mois d'observation
- Export CSV des tickets, export/import JSON de sauvegarde complète

## 💾 Données

Tout est stocké **localement dans votre navigateur** (rien n'est envoyé sur internet). Pensez à utiliser régulièrement le bouton **⬇ Sauvegarder** (en haut à droite) : le fichier JSON créé peut être rechargé via **⬆ Restaurer**, par exemple pour changer d'appareil ou de navigateur.
