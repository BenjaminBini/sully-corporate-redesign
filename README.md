#Redesign du site officiel de Sully Group

Travail sur le redesign [du site officiel](http://www.sully-group.fr) de Sully Group.

Le site repose sur le micro-CMS [Pico](https://github.com/picocms/Pico).

Uniquement la page d'accueil a été réalisée pour l'instant.

Cette démonstration est accessible à cette adresse : [sully.bini.io](http://sully.bini.io).

## Prérequis
Afin d'installer sur votre machine cette démonstration, assurez-vous d'avoir installé [compass](http://compass-style.org/), [Bower](http://bower.io/), [Composer](https://getcomposer.org/) et [php](http://php.net/).

## Installation
Téléchargez les sources et exécutez la commande suivante depuis le répertoire racine de celles-ci :
```
composer install
```

Exécutez ensuite les commandes suivantes depuis le répertoire `/themes/sully`.

```
bower install
compass compile
```

Placez les sources dans un répertoire rendu accessible via un serveur comme [Apache](https://httpd.apache.org/) ou [nginx](http://nginx.org/) avec le module php installé et activé.