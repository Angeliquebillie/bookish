# BOOKISH — application personnelle

## Contenu
- Application web progressive (PWA) installable sur iPhone depuis Safari.
- Fonctionne hors connexion après son premier chargement pour les fonctions principales.
- Données conservées localement dans le navigateur de l'appareil.
- Bibliothèque, statuts, progression, PAL mensuelle, wishlist, sagas, tropes, avis, citations, statistiques, export/import JSON.

## Publication nécessaire
Une PWA doit être servie depuis une adresse HTTPS pour être installée sur iPhone. Ce dossier n'est pas encore publié et ne crée pas automatiquement une application sur le téléphone.

### Publication simple avec GitHub Pages
1. Crée un dépôt GitHub privé ou public nommé `bookish`.
2. Dépose tous les fichiers de ce dossier à la racine du dépôt.
3. Dans Settings > Pages, active le déploiement depuis la branche principale (root).
4. Attends l'adresse HTTPS fournie par GitHub Pages.
5. Ouvre cette adresse dans Safari sur l'iPhone > bouton Partager > Sur l'écran d'accueil > Ajouter.

Attention : un dépôt GitHub privé ne rend pas forcément le site Pages privé selon les réglages et l'offre. Pour un usage strictement privé, choisir un hébergement avec contrôle d'accès ou une solution de publication privée.

## Sauvegardes et confidentialité
Les fiches sont enregistrées dans le stockage local du navigateur (localStorage). Elles ne sont pas synchronisées entre appareils. Utilise régulièrement « Exporter ma bibliothèque ». Ne partage pas le fichier JSON : il contient tes notes personnelles.
Les couvertures via URL nécessitent internet et l'hébergeur de l'image peut recevoir une requête lors de l'affichage. La recherche de catalogue externe n'est pas encore intégrée à cette version.

## Limites
Cette version est une PWA, pas une application native publiée sur l'App Store. Pour une synchronisation multi-appareils, authentification ou sauvegarde cloud, il faudra ajouter un backend sécurisé.
