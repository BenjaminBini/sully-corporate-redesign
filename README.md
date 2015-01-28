# Redesign of Sully Group official website

Draft of the redesign of the [official website](http://www.sully-group.fr) of Sully Group.

The website is based on [Pico micro-CMS](https://github.com/picocms/Pico).

Only the index page has been made for now.

This demo is available at this URL : [sully.bini.io](http://sully.bini.io).

## Prerequisite
To install this demo on your computer, be sure that you have installed [compass](http://compass-style.org/), [Bower](http://bower.io/), [Composer](https://getcomposer.org/), and [php](http://php.net/).

## Installation
Download the sources and run the following command from the project root directory :

```
composer install
```

Then, run the following command from `/themes/sully` directory.

```
bower install
compass compile
```

Put the sources in a directory accessible by a web server like [Apache](https://httpd.apache.org/) ou [nginx](http://nginx.org/) with php module activated.