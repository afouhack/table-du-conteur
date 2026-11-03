# Table du Conteur

Outils du Conteur pour le jeu de rôle **Coureurs d'Orages** (Islayre d'Argolh), compagnon de la [Forge de Coureurs](https://afouhack.github.io/Forge-de-Coureurs/) :

- **Accueil** : nouvelle partie en quatre étapes (univers, groupe, one-shot ou campagne, œuvre). Chaque étape terminée se résume en une ligne, pour voir tous les choix d'un coup d'œil avant de lancer ; on la rouvre d'un clic. Ou reprise d'une partie en cours.
- **Groupe** : chaque coureur a son nom et son niveau, et peut être marqué présent ou absent. Un mort, un absent, une montée de niveau : les rencontres suivent aussitôt.
- **Aventure** : tout part d'une œuvre de référence parmi 60 (Alien, Fallout, Jumanji, Star Wars, Sherlock Holmes, Jurassic Park, Terminator, Titanic…), ou d'une œuvre tirée au hasard. Elle est transposée dans l'univers choisi sans reprendre son histoire ni ses personnages : les œuvres naturelles dans l'univers sont signalées d'une étoile, les plus incohérentes sont masquées, et l'aventure indique ce qui remplace le ressort d'une œuvre transposée. Chaque œuvre a sa propre histoire, écrite pour être transposée dans les 14 univers grâce à un vocabulaire propre à chacun (lieux, rôles, objets, créatures). Un one-shot tient sur une page : l'histoire en deux mots, le point de départ, trois pistes à explorer dans l'ordre voulu (chacune dit ce qu'on y voit, qui on y croise, ce qu'on y gagne et ce qui se passe si ça rate), le moment où ça tourne mal, le climax (avec ce que les pistes y changent et plusieurs façons de s'en sortir), un secret, et les fiches des personnages. Les combats sont choisis par l'histoire et calibrés selon le groupe. Personnages et lieux se changent d'un clic, le texte suit. La campagne suit la forme du Val des Corbeaux : fil rouge en trois points clés, plan de l'antagoniste, trois factions, factions cachées au d12, sept lieux, table de rencontres 1d4 + 1d8, chapitres.
- **Bestiaire** : les 24 créatures du livre, 15 animaux sauvages (loups, ours, crocodile, requin, éléphant…), 17 dinosaures et monstres préhistoriques (dont mammouth et ours des cavernes), 14 créatures magiques et mythiques (avec dés de vilenie pour les plus redoutables), des figurants construits avec sa méthode, et une dizaine d'adversaires « rhabillés » par thème. Rencontres calibrées selon le groupe (estimation maison : le livre ne cherche pas l'équilibre). Création de créatures selon la méthode du livre.
- **Combat** : combats proposés selon les coureurs présents, jauge de difficulté, initiative de groupe au d6, PV par créature, rangs serrés (le surplus de dégâts passe à la suivante), capacités spéciales expliquées, flammes jamais deux tours de suite, dés de vilenie, états, journal.
- **En jeu** : personnages, butin et parchemins lisibles selon le niveau, dangers à l'échelle du livre, réputation, dés, aide-mémoire.
- **Notes** : notes libres, journal des séances, personnages gardés.

Chaque section se replie d'un clic sur son titre (« Tout replier » / « Tout déplier » en haut de chaque onglet), et l'état est mémorisé.

Tout tient dans `index.html`. Les parties sont enregistrées dans le navigateur de chaque appareil ; un code de sauvegarde permet de les passer d'un appareil à l'autre.

## Mettre en ligne avec GitHub Pages

1. Crée un dépôt sur GitHub (par exemple `table-du-conteur`).
2. Dépose tout le contenu de ce dossier à la racine du dépôt (`index.html`, `manifest.webmanifest`, les icônes, `.nojekyll`).
3. Dans le dépôt : **Settings → Pages → Build and deployment**, source **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
4. Après une minute, l'outil est disponible à `https://TON-PSEUDO.github.io/table-du-conteur/`.

## Crédits

- Coureurs d'Orages : jeu d'Islayre d'Argolh, illustrations et mise en page de John Grümph. Les textes de règles cités ici sont des résumés ; le jeu complet se trouve dans le livre.
- Polices : Google Fonts.
