Le dossier visualisation comporte les notebooks relatif à la première analyse visuelle du signal. 

Les trois couleurs représentent les trois axes d’accélération X, Y, Z dans un espace tridimensionnel:
- Bleu : Représente les données d’accélération sur l’axe X, associé au mouvement latéral (gauche-droite).
- Orange : Représente les données sur l’axe Y, correspondant au mouvement d’avant en arrière.
- Vert : Représente les données sur l’axe Z, associé au mouvement vertical (haut-bas).

Ces données sont enregistrées par l’accéléromètre intégré dans le capteur AX3.

# Utilisation du filtre passe-bas de Butterworth

Le filtre Butterworth permet de supprimer les fréquences élevées (le bruit), tout en conservant les tendances principales du signal. Les signaux sont plus lissés, ce qui facilite l’analyse des variations générales dans le temps. Après filtrage, les variations dues à des artefacts aléatoires ont disparu, laissant uniquement les oscillations principales, liées aux mouvements périodiques (comme la course, les sauts, ou les balancements du corps).

# ENMO

L’ENMO (Euclidean Norm Minus One) est une mesure couramment utilisée pour quantifier l’intensité de l’activité physique à partir des données d’accéléromètres. Un seuil d’ENMO supérieur à 0,1 g est souvent utilisé pour indiquer une activité physique d’intensité modérée à vigoureuse. Cependant, ce seuil peut varier en fonction de la population étudiée et des objectifs spécifiques de l’étude. Il est donc recommandé de consulter la littérature scientifique pertinente ou de calibrer le seuil en fonction des caractéristiques spécifiques de votre échantillon de données.

L’ENMO étant basé sur la norme euclidienne, il est souvent plus représentatif sans filtrage.
