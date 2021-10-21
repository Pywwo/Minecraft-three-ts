# MINECRAFT CLONE IN TYPESCRIPT

Projet HUB (libre de choix et de technologie) d'une durée de 2 mois en 3ème année, accompagné de Romain FOUYER et de Charlie JEANNEAU.

Le but était de faire un jeu Voxel en 3d dans le navigateur, avec la librairie THREE.js.

Ce projet contient:
- Un ECS typescript utilisé dans tout le jeu https://en.wikipedia.org/wiki/Entity_component_system 
- Un générateur de bruit de perlin afin de générer des cartes infinies et aléatoires https://fr.wikipedia.org/wiki/Bruit_de_Perlin
- Une gestion de la physique faite avec le plugin CANNON, que nous avons encapsulé dans un system de l'ECS.
- Une séparation en chunk de la carte, afin de créer un chargement de la carte en dynamique, et de libérer la mémoire des chunks non allouées
- Un système d'animaux et de reproduction de ces derniers.
- Un système de raycast Voxel et de jeu de lumières.
- Un système de caméras modifiable via l'ECS (mais en first-person de base).
- Une multitude de micro voire très grosses optimisation de nos différentes librairies et de code, puisque le développement 3d dans le navigateur coute énormément de ressources.

## Usage

### Install Typscript

```
npm install typescript -g
```

### Start

```
$ npm install # or yarn
$ npm start
```