# 🏠 Maison & Repas

Application HTML autonome (un seul fichier, aucune dépendance, fonctionne hors ligne) pour organiser les repas de la maison : **menus de la semaine, liste de courses et budget**, alimentée par la saisie des tickets de caisse.

## 🚀 Ouverture

Téléchargez `organisation-repas.html` puis ouvrez-le d'un double-clic dans n'importe quel navigateur (ordinateur, tablette ou téléphone). Aucune installation, aucun compte, aucune connexion internet nécessaire.

## 📅 Menus

- Planning hebdomadaire : 7 jours × midi/soir, navigation semaine par semaine
- Bouton « Proposer un menu » : remplit la semaine à partir de vos recettes
- 8 recettes familiales pré-chargées (pour 4 personnes), modifiables et complétables avec vos propres recettes (ingrédients + quantités)

## 🛒 Courses

- **Génération automatique de la liste** depuis les recettes du menu (quantités ajustées pour 4 personnes, ingrédients agrégés)
- Liste organisée par rayon (8 catégories), cases à cocher, ajout manuel, impression, copie
- Conseils anti-gaspillage et routines de courses intégrés

## 💰 Budget

- **Saisie des tickets de caisse** : article, catégorie (devinée automatiquement), quantité, prix
- **Collage direct du texte du ticket** : photo du ticket → Google Lens (ou OCR du téléphone) → copier-coller ; l'application extrait les lignes « nom … prix » et ignore TOTAL / TVA / ESPÈCES
- Tableau de bord : dépenses du mois, panier moyen, dépense hebdomadaire moyenne, répartition par catégorie, évolution sur 6 mois
- Suivi vs objectif mensuel + historique ; l'objectif peut être défini après 1-2 mois d'observation
- Export CSV des tickets, export/import JSON de sauvegarde complète

## 💾 Données

Tout est stocké **localement dans votre navigateur** (localStorage du fichier ouvert). Pensez à utiliser régulièrement le bouton **⬇ Sauvegarder** (en haut à droite) : le fichier JSON créé peut être rechargé via **⬆ Restaurer**, par exemple pour changer d'appareil ou de navigateur.
