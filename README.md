# ![Formation GoLogic Example de Projet](Gologic.png)

## Pré-requis pour l'exemple de projet 

(Anglais à suivre)

Nous sommes ravis d'explorer GitHub Copilot avec vous à travers des exemples pratiques. Pour assurer un bon déroulement, veuillez préparer votre poste de travail de la manière suivante :

- Installer Visual Studio Code : [https://code.visualstudio.com/download](https://code.visualstudio.com/download)

- Une fois que Visual Studio Code est installé sur votre système, installez le plugin SonarLint (Ouvrez VSCode, appuyez sur Ctrl+Shift+X, saisissez "SonarLint" dans la barre de recherche, puis cliquez sur "Install").

- Installer la version plus récente de NodeJS et NPM : [https://nodejs.org/en/download/prebuilt-installer](https://nodejs.org/en/download/prebuilt-installer) (On recommande l'installeur automatique pour faciliter le tout).

- (OPTIONNEL) Installer Postman pour faciliter les requêtes au backend : [https://www.postman.com/downloads/](https://www.postman.com/downloads/)

## Démarrer l'application

- Ouvrez VSCode et ouvrez une nouvelle fenêtre (Ctrl+Shift+N).

- Sur la page d'accueil, cliquez sur "Clone Git Repository...", entrez l'URL de ce dépôt [https://github.com/gologic-ca/Exemple-React-Redux-GHCopilot.git](https://github.com/gologic-ca/Exemple-React-Redux-GHCopilot.git) et confirmez en cliquant sur "Clone from the URL". Cliquez ensuite sur "Open".

- Une fois le projet ouvert, ouvrez un nouveau terminal (Shift+Ctrl+\`). Exécuter la commande :
`npm install`
Après que l'installation est complète, exécuter la commande :
`npm start`

Félicitations, le projet devrait maintenant être en cours d'exécution sur `http://localhost:3000/`.

## Structure de fichiers
* `src/components` Contient tous les composants fonctionnels.
* `src/components/Pages` Contient les composants utilisés par le routeur comme pages.
* `src/state` Contient le code lié à Redux.
* `src/services` Contient le code qui interagit avec les systèmes externes (requêtes API).
* `src/types` Contient les définitions de types ainsi que le code lié à ces types.
* `src/config` Contient les fichiers de configuration.

## [Source et documentation](https://github.com/gothinkster/realworld)

La base de code contient des exemples concrets (CRUD, authentification, modèles avancés, etc.) qui respectent la spécification et l'API [RealWorld](https://github.com/gothinkster/realworld-example-apps).

Cette base de code a été créée pour montrer une application full-stack complète construite avec Java Spring (avec une orientation fonctionnalité) incluant des opérations CRUD, de l'authentification, du routage, de la pagination, et plus encore.

Pour plus d'informations sur le fonctionnement avec d'autres frontends/backends, rendez-vous sur le dépôt [RealWorld](https://github.com/gothinkster/realworld).


# ![Formation GoLogic Example de Projet](Gologic.png)

## Prerequisites 

We couldn't be more excited to explore GitHub Copilot with you via practical examples. To ensure a smooth process, please prepare your workstation as follows:

- Install Visual Studio Code : [https://code.visualstudio.com/download](https://code.visualstudio.com/download)

- Once Visual Studio Code is installed on your system, install the SonarLint plugin (Open VSCode, click Ctrl+Shift+X, insert "SonarLint" in the search bar and click on "Install").

- IInstall the most recent version of NodeJs and NPM : [https://nodejs.org/en/download/prebuilt-installer](https://nodejs.org/en/download/prebuilt-installer) (We recommend the auto-installer to facilitate the whole).

- (OPTIONAL) Install Postman to facilitate testing API calls to the backend : [https://www.postman.com/downloads/](https://www.postman.com/downloads/)

## Start the application

- Open VSCode and open a new window (Ctrl+Shift+N).

- On the landing page, click on "Clone Git Repository...", enter the URL of the example repository [https://github.com/gologic-ca/Exemple-React-Redux-GHCopilot.git](https://github.com/gologic-ca/Exemple-React-Redux-GHCopilot.git) and confirm your selection by clicking "Clone from the URL". Then, click on "Open".

- Once the project is open, open a new terminal (Shift+Ctrl+\`). Execute the following command :
`npm install`
After the installation is complete, execute the start command :
`npm start`

Congratulations, the project is now running locally on your machine at : `http://localhost:3000/`.

## Folder Structure
* `src/components` Contains all the functional components.
* `src/components/Pages` Contains components used by the router as pages.
* `src/state` Contains the Redux-related code.
* `src/services` Contains the code that interacts with external systems (API requests).
* `src/types` Contains type definitions and related code.
* `src/config` Contains configuration files.

## [Source and Documentation](https://github.com/gothinkster/realworld)

The codebase contains concrete examples (CRUD, authentication, advanced patterns, etc.) that adhere to the [RealWorld](https://github.com/gothinkster/realworld-example-apps) specification and API.

This codebase was created to showcase a complete full-stack application built with Java Spring (feature-oriented) including CRUD operations, authentication, routing, pagination, and more.

For more information about operating with other frontends/backends, visit the [RealWorld](https://github.com/gothinkster/realworld) repository.
