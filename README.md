# xgboost-factory-builder

J'aimerais avoir l'implémentation from scratch de l'lagorithme XGboost from scratch en Python en utilisant la combinaison de Design Pattern Factory pour créer les différents types d'arbres de manière flexible et extensi
ble, Builder pour construire de manière progressive et modulaire les différents composants de l'algorithme XGBoost, comme les arbres de décision, la fonction de perte, les règles de split, Composer pour représenter la structure hiérarchique de l'ensemble des arbres de décision, permettant ainsi de les traiter de manière uniforme, Decorator pour ajouter dynamiquement des comportements spécifiques aux arbres de décision, comme des fonctions d'élagage, de régularisation, Strategy pour encapsuler les différentes stratégies d'optimisation (gradient descendant, Newton-Raphson, etc.) utilisées par XGBoost, permettant ainsi de les changer facilement, et Observer pour mettre en place un système d'événements permettant de suivre l'évolution de l'entraînement de l'algorithme XGBoost (convergence, overfitting, etc.)

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/xgboost-factory-builder.git
cd xgboost-factory-builder
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
