Prérequis
Visual Studio Code (ou votre éditeur de code préféré ou IDE)
Git
NodeJS 
NPM 

Installation et lancement de l'application

Effectuez un fork de ce dépôt
Cliquez sur le bouton "fork" en haut à droite de la page du dépôt sur GitHub.

Clonez le dépôt forké sur votre machine locale
Remplacez l'URL ci-dessous par l'URL de votre dépôt forké.
https://github.com/votre-nom-utilisateur/nom-du-depôt-forké.git

Ouvrez une fenêtre de terminal et accédez au répertoire qui stockera votre projet.
cd nom-du-depôt-forké

Dans votre terminal, exécutez la commande ci-dessous. Le point "." à la fin de la commande clonera le projet dans le répertoire actuel.
git clone https://github.com/votre-nom-utilisateur/nom-du-depôt-forké.git .

Installez les dépendances
Dans votre terminal, exécutez les commandes ci-dessous pour installer les dépendances répertoriées dans le fichier package.json.

npm install

Lancez l'application
Dans votre terminal, exécutez la commande ci-dessous pour lancer le serveur de développement.

ng serve


L'application se lancera dans votre navigateur à l'adresse http://localhost:4200. Elle se rechargera automatiquement si vous modifiez l'un des fichiers source.

Construisez l'application
Dans votre terminal, exécutez la commande ci-dessous pour construire l'application pour la production.

ng build

Les artefacts de construction seront stockés dans le répertoire dist/.

Gestion des sauvegardes régulières avec GitHub

Pour assurer la sauvegarde régulière de votre travail sur GitHub, suivez ces étapes :

Ajoutez et validez les modifications
Dans votre terminal, utilisez les commandes suivantes pour ajouter les fichiers modifiés et valider les changements.
Les artefacts de construction seront stockés dans le répertoire dist/.

Gestion des sauvegardes régulières avec GitHub
Pour assurer la sauvegarde régulière de votre travail sur GitHub, suivez ces étapes :

Ajoutez et validez les modifications
Dans votre terminal, utilisez les commandes suivantes pour ajouter les fichiers modifiés et valider les changements.
Les artefacts de construction seront stockés dans le répertoire dist/.

Gestion des sauvegardes régulières avec GitHub
Pour assurer la sauvegarde régulière de votre travail sur GitHub, suivez ces étapes :

Ajoutez et validez les modifications

Dans votre terminal, utilisez les commandes suivantes pour ajouter les fichiers modifiés et valider les changements.
git add .
Poussez les modifications sur GitHub
git commit -m "Description de vos modifications"

Poussez les changements vers votre dépôt forké sur GitHub en utilisant la commande suivante.
git push origin nom-de-votre-branche

Cela garantit que vos sauvegardes sont régulièrement mises à jour sur votre dépôt GitHub. Répétez ces étapes chaque fois que vous souhaitez sauvegarder vos modifications.
