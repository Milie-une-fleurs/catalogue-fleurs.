CATALOGUE MILIE UNE FLEURS — PREMIÈRE VERSION

Contenu :
- index.html, style.css, app.js : application
- manifest.json, sw.js : installation et fonctionnement hors connexion
- icon-192.png et icon-512.png : icônes

Mise en ligne :
Déposer TOUS les fichiers à la racine du dépôt GitHub, puis activer Settings > Pages > Deploy from a branch > main > /(root).

Sur iPhone :
Ouvrir l'adresse HTTPS dans Safari, attendre le chargement, puis Partager > Sur l'écran d'accueil.

Données :
Les créations et photos sont enregistrées dans IndexedDB sur l'appareil. Le dépôt GitHub ne reçoit pas les données.
Exporter régulièrement une sauvegarde JSON et la conserver sur un ordinateur.
La première installation nécessite une connexion internet. Le service worker met en cache l'application pour une utilisation ultérieure hors connexion.

Important :
Ceci est une première version à tester avec quelques créations fictives avant d'y saisir les données réelles. Tester aussi l'export et la restauration.
