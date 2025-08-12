# Ethereum Todo List DApp

Ce projet est un **DApp (application décentralisée)** — une liste de tâches ("Todo List") opérant sur la blockchain Ethereum, construit selon le tutoriel vidéo *“Build Your First Blockchain App – Ethereum Todo List”* de Dapp University :contentReference : (https://www.youtube.com/watch?v=rzvk2kdjr2I&t=4716s&ab_channel=DappUniversity).

---

## 1. Fonctionnalités principales

- Ajout de tâches (todos) via un smart contract Solidity.
- Marquage des tâches comme complétées.
- Interface web React qui interagit avec le contrat intelligent via Web3.js.
- Déploiement sur un réseau local (Ganache) ou testnet Ethereum (Ropsten, Rinkeby…).

---

## 2. Technologies utilisées

| Technologie | Rôle dans le projet |
|-------------|----------------------|
| **Solidity** | Écriture du smart contract pour gérer les todos |
| **Web3.js** | Interaction depuis le front-end avec Ethereum |
| **React.js** | Interface utilisateur (UI) dynamique |
| **Ganache** ou **Truffle Develop** | Blockchain locale pour tests |
| **MetaMask** | Portefeuille Ethereum pour tester les interactions |
| (Optionnel) **Truffle Framework** | Compilation, tests, migrations de contrats |

---

## 3. Installation & mise en route

1. **Cloner le dépôt**  
```bash
   git clone <URL_DU_DEPOT>
   cd <NOM_DU_PROJET>
```
2. **Installer les dépendances**
```bash   
   npm install
```
3. **Démarrer une blockchain locale**
- Avec Ganache GUI ou CLI :
```bash
  ganache-cli
```
4. **Compiler et déployer le contrat**
```bash
truffle compile
truffle migrate --network develop
```
5. **Lancer l’interface React**
```bash
npm start
```
6. **Ouvrir l’application dans ton navigateur**
   
Visite (http://localhost:3000) et connecte ton MetaMask au réseau local.
