# RzCinemaHtml

La page de lecture de rzCinema, l'addon cinéma du serveur LeZbeul, publiée avec GitHub Pages.

**Adresse :** https://rayzox57.github.io/RzCinemaHtml/player.html

## Pourquoi elle est en ligne

Le jeu garde une copie de cette page dans son Lua et l'ouvre pour les fichiers (vidéo, audio, image). Mais le lecteur de YouTube refuse une page qui ne peut pas dire sur quel site elle se trouve (erreur 153). Pour YouTube, et pour Vimeo quand une vidéo est réservée à certains sites, la page doit donc être servie par un vrai site en https : c'est ce dépôt.

## Brancher le serveur dessus

Dans les réglages de rzCinema, section « Vidéos », ou en console serveur :

    rzCinema_player_page_sv "https://rayzox57.github.io/RzCinemaHtml/player.html"

## Mettre à jour

`player.html` est une copie exacte de `rzcinema/html/player.html`. Quand celle de l'addon change, recopie-la ici et publie-la. La page annonce sa `VERSION` au jeu, qui prévient dans sa console quand la copie en ligne est plus ancienne que l'addon.

Rien d'autre n'est à publier : `inject.js` reste dans l'addon. `.nojekyll` dit à GitHub Pages de servir les fichiers tels quels.
