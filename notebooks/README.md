Le dossier visualisation comporte les notebooks relatif à la première analyse visuelle du signal. 

Les trois couleurs représentent les trois axes d’accélération X, Y, Z dans un espace tridimensionnel:
- Bleu : Représente les données d’accélération sur l’axe X, associé au mouvement latéral (gauche-droite).
- Orange : Représente les données sur l’axe Y, correspondant au mouvement d’avant en arrière.
- Vert : Représente les données sur l’axe Z, associé au mouvement vertical (haut-bas).

Ces données sont enregistrées par l’accéléromètre intégré dans le capteur AX3.

# Utilisation du filtre passe-bas de Butterworth

Le filtre Butterworth permet de supprimer les fréquences élevées (le bruit), tout en conservant les tendances principales du signal. Les signaux sont plus lissés, ce qui facilite l’analyse des variations générales dans le temps. Après filtrage, les variations dues à des artefacts aléatoires ont disparu, laissant uniquement les oscillations principales, liées aux mouvements périodiques (comme la course, les sauts, ou les balancements du corps).
