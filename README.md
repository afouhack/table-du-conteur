# Table du Conteur

Outils du Conteur pour le jeu de rôle **Coureurs d'Orages** (Islayre d'Argolh), compagnon de la [Forge de Coureurs](https://afouhack.github.io/Forge-de-Coureurs/) :

- **Accueil** : nouvelle partie en six étapes (univers, groupe, one-shot ou campagne, type d'aventure, œuvres, éléments imposés). Chaque étape terminée se résume en une ligne, pour voir tous les choix d'un coup d'œil avant de lancer ; on la rouvre d'un clic. Ou reprise d'une partie en cours.
- **Groupe** : chaque coureur a son nom et son niveau, et peut être marqué présent ou absent. Un mort, un absent, une montée de niveau : les rencontres suivent aussitôt.
- **Aventure** : huit types (enquête, horreur, exploration, casse, escorte, siège, intrigue, chasse) et 59 œuvres de référence « dans l'esprit de… » (Alien, Fallout, Star Wars, Sherlock Holmes, Jurassic Park, Terminator, Titanic, Lovecraft, Pirates des Caraïbes…), transposées dans n'importe quel univers sans reprendre leur histoire ni leurs personnages. Un ou deux types et une ou deux œuvres se choisissent au clic et se combinent. Un one-shot est une situation, pas des rails : un problème de départ et son compte à rebours, trois pistes à jouer dans n'importe quel ordre (chacune rapporte un atout), un climax où l'adversaire agit (plan en cours, otage, marché corrompu ou fuite) avec plusieurs façons de s'en sortir, et un grain de sable. La campagne suit la forme du Val des Corbeaux : fil rouge en trois points clés, plan de l'antagoniste, trois factions, factions cachées au d12, sept lieux, table de rencontres 1d4 + 1d8, chapitres. Chaque élément se relance, chaque texte se retouche.
- **Boîte à outils du Conteur** : jusqu'à deux éléments imposés parmi 89 : quatre propres à chaque univers (saloon, arcologie, galion fantôme, grotte ornée…), des éléments communs (phare, train, fête foraine, mine engloutie…) et des événements (carnaval, éclipse, mariage…). L'élément devient le cœur de l'aventure : sa fonction dans l'histoire, une règle de jeu, les lieux des pistes et du climax, son effet pendant l'affrontement final et le dernier cran du compte à rebours. Selon le type : suspects pour l'enquête fermée, vagues pour le siège, chose qui avance seule pour l'escorte, dette à payer pour le pillage.
- **Pour animer** : compte à rebours cliquable, atouts à cocher qui recalculent la difficulté du climax, et pour chaque piste une ambiance à décrire en arrivant et une solution si les joueurs bloquent.
- **Bestiaire** : les 24 créatures du livre, 9 dinosaures et monstres préhistoriques, 14 créatures magiques et mythiques (avec dés de vilenie pour les plus redoutables), des figurants construits avec sa méthode, et une dizaine d'adversaires « rhabillés » par thème. Rencontres calibrées selon le groupe (estimation maison : le livre ne cherche pas l'équilibre). Création de créatures selon la méthode du livre.
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
