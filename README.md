# docker-compose-vue
zf200625.1014

<!-- TOC titleSize:2 tabSpaces:2 depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 skip:1 title:1 charForUnorderedList:* -->
## Table of Contents
* [Build Setup](#build-setup)
* [Remarques](#remarques)
* [Utilisation](#utilisation)
* [Documentation](#documentation)
  * [Insert Update and Delete records from MySQL with Vue.js](#insert-update-and-delete-records-from-mysql-with-vuejs)
<!-- /TOC -->

A simple docker-compose vue with the template from https://github.com/vuejs-templates/webpack.

The dockerfile from https://vuejs.org/v2/cookbook/dockerize-vuejs-app.html#Real-World-Example.

## Build Setup
```
docker-compose up --build
```
after
```
docker-compose up -d
```

## Remarques

Il y a pleins d'erreurs avec le nouveau Node 14.x, je ne sais pas pourquoi et je n'ai pas eu le temps de chercher. Mais cela fonctionne quand même !


## Utilisation

ATTENTION:
Il faut attendre un certain temps que tout soit *installé* dans le container pour que la page web soit *utilisable* !

http://0.0.0.0:8080/#/

Après si on modifie la ligne 91 du fichier:
```
src/components/HelloWorld.vue
```

En **temps réel** on doit pouvoir voir sur la page WEB la modification faite !




For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


## Documentation
### Insert Update and Delete records from MySQL with Vue.js

https://makitweb.com/insert-update-delete-records-from-mysql-with-vue-js/



