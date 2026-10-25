# Gestion 💶 — première version

Application web progressive (PWA) de budget personnel, conçue pour mobile et iPhone.

## Fonctionnalités
- Tableau de bord mensuel, revenus, dépenses et solde du mois.
- Graphique en donut par catégorie.
- Ajout, modification et suppression d'opérations.
- Prélèvements récurrents prévisionnels.
- Statistiques et plafond de dépenses mensuel.
- Thème clair/sombre/système.
- Export JSON, restauration JSON et export CSV.
- Stockage local dans le navigateur.

## Installation sur iPhone
Une PWA doit être servie via HTTPS pour être installable et fonctionner hors ligne. Le moyen gratuit le plus simple est de publier ces fichiers sur GitHub Pages (ou un hébergeur statique HTTPS équivalent), puis :
1. Ouvrir l'adresse HTTPS dans Safari sur l'iPhone.
2. Toucher le bouton Partager.
3. Choisir « Sur l’écran d’accueil » puis « Ajouter ».
4. Ouvrir Gestion 💶 depuis la nouvelle icône.

## Important
- Les données restent dans le stockage local du navigateur sur cet appareil.
- Exporter régulièrement une sauvegarde JSON depuis Réglages.
- Cette version ne se connecte pas à la banque et ne déclenche pas encore de notifications système.
- Les prélèvements récurrents sont des prévisions et ne créent pas automatiquement de dépenses réelles.
- Le solde affiché sur l'accueil est le résultat des opérations du mois sélectionné ; le solde global cumulatif est disponible dans Réglages/solde de départ à compléter pour refléter le solde antérieur.
