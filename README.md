## 🚀 Démarrage rapide

### 1. Installez le logiciel requis

 * [Node.js](https://nodejs.org/en/download/)

### 2. Forker le référentiel


### 3. Exécutez l'exemple de jeu

Le dépôt inclut l'exemple de jeu Breakout de [Phaser 3.0](http://phaser.io/).

Depuis le répertoire du projet :

* `installation npm`
* `npm start`

## 4. Déployer sur IPFS

Pour déployer sur IPFS, nous devons suivre les étapes suivantes :

* Récupérez les clés API de [Pinata](https://pinata.cloud/)

  *PINATA_API_KEY
  *PINATA_API_SECRET_KEY

* Saisissez ces clés en tant que <a href="../../settings/secrets/actions">Secrets du référentiel</a>

* Accédez au <a href="../../actions/workflows/release.yaml">Release Workflow</a> sur Github Actions et cliquez sur « Exécuter le workflow »

* Le jeu est maintenant déployé et est accessible à l'aide des passerelles IPFS répertoriées dans les <a href="../../releases">Notes de version</a>

