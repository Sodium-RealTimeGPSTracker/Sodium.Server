# Sodium Server

Le projet ci-présent vise le serveur WebSocket et le client web

## Pour installer les dépendances

Nécessite node et npm

`npm install`

## Pour démarrer le serveur

`node server.js`

## Pour le tester

Après avoir démarré le serveur et le tracker, on peut voir le tracé du parcours en live sur le client web webapp.html.

## Problèmes connus

Avec Chrome, lorsque l'on ferme ou rafraîchit le client web, il se pourrait que le serveur plante.
Il faut redémarrer le serveur et ensuite le tracker quand ça se produit.

Avec Firefox, l'interface de la carte est un peu brisé
