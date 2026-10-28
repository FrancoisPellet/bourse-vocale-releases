# Bourse Vocale

Application Android qui lit à voix haute, en français, les cours d'une liste de valeurs boursières et leurs dernières actualités, ainsi que le bilan d'un portefeuille d'actions. Pensée pour une personne malvoyante : tout est utilisable sans lire l'écran.

<p align="center">
  <img src="captures/portefeuille.png" width="240" alt="Page Portefeuille : total du portefeuille, puis chaque valeur avec le nombre d'actions, le prix de revient et la plus-value en vert ou la moins-value en rouge, bouton jaune « Lire le portefeuille »">
  &nbsp;&nbsp;
  <img src="captures/valeurs.png" width="240" alt="Page Valeurs : liste des valeurs avec cours et variation du jour, bouton jaune « Lire les cours »">
  &nbsp;&nbsp;
  <img src="captures/actualites.png" width="240" alt="Page Actualités : dernier article BFM Bourse de chaque valeur, bouton jaune « Lire les actualités »">
</p>

- **Portefeuille** (glisser vers la droite) : le bouton jaune lit le total puis chaque ligne détenue, avec sa plus-value ou sa moins-value en euros et en pourcentage. Toucher une valeur la lit seule ; un appui long ouvre sa fiche pour acheter ou vendre des actions, avec confirmation lue à voix haute.
- **Valeurs** : le gros bouton jaune lit tous les cours ; toucher une valeur la lit seule. Le bouton vert ajoute une valeur, par dictée vocale.
- **Actualités** (glisser vers la gauche) : le bouton jaune lit les titres, avec la date et la source ; toucher une actualité lit l'article, un appui long propose de l'ouvrir dans le navigateur.

Chaque page s'annonce à voix haute quand on y arrive. La voix et la vitesse de lecture sont celles réglées dans Android (Paramètres → Accessibilité → Synthèse vocale).

## Installer

Sur le téléphone Android, toucher ce lien :

**[Télécharger la dernière version](https://github.com/FrancoisPellet/bourse-vocale-releases/releases/latest/download/bourse-vocale.apk)**

Au premier téléchargement, Android demande d'autoriser l'installation depuis le navigateur : accepter, puis ouvrir le fichier.

Pour les mises à jour, le même lien donne toujours la dernière version. L'application [Obtainium](https://github.com/ImranR98/Obtainium) peut aussi les proposer automatiquement : y ajouter l'adresse de ce dépôt.

Ce dépôt ne contient que les APK publiés ; le code source est privé.
