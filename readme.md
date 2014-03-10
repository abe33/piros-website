
# Piros Website

### Install

D'abord, il vous faut installer [Node.js](http://nodejs.org/), ainsi qu'un client Git, je vous recommande [Le client officiel de Github pour Windows](http://windows.github.com/).

Pour un tutorial détaillé de l'installation de Node sur Windows, vous pouvez trouver tout ça [ici](http://dailyjs.com/2012/05/03/windows-and-node-1/), seule la première partie concernant l'installation va vous intéresser.

Une fois Git et Node correctement installé, il est maintenant temps d'installer
la suite.

#### Wintersmith

Wintersmith est le moteur de génération de sites statique, il est recommandé de l'installer globalement avec la commande suivante :

```
npm install -g wintersmith
```

Un fois l'installation effectuée on peut installer les dépendences du projet:

Naviguez vers le répertoire où vous avez télécharger le projet Git du site de Piros. Ouvrez un invite de commande dans ce répertoire et saississez :

```
npm install
```

Une fois les dépendences installées on va pouvoir démarrer le serveur local de test.

### Local Server

Pour lancer le server il suffit de saisir dans la console :

```
wintersmith preview
```

Si tout s'est bien déroulé, le serveur devrait être accessible sur `localhost:8080`.

### Construire le site

Pour générer le site final, il suffit de saisir dans la console :

```
wintersmith build
```

Et voila :)
