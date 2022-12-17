Pour le moment je ne suis qu'au début du projet.


J'ai corrigé :

- Les images qui font maintenant 10% de leur taille initiale;
- Les bouttons filter qui affichent maintenant un background doré quand on a cliqué dessus;
- Mis les balises script en bas de page, car cela peut causer des problèmes;
- Ligne 126: Pour afficher l'image précédente
activeImage = $(this)
=> 
activeImage = -1;

Restant à faire:

- Tout le SEO;
- Encore beaucoup de choses à optimiser;
- Afficher un carrousel d'image qui marche dans le portfolio;
- Ajouter les balises meta;