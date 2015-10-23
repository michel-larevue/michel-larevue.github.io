# Michel La Revue

Site web fabriqué avec [Jekyll](http://jekyllrb.com/) et hébergé avec [Github Pages](https://pages.github.com/).

    jekyll s

## Structure des répertoires et fichiers

 - _config.yml : Config Jekyll
 - index.html : Contenu de l'accueil
 - articles/ : Articles
 - pages/ : Pages
 - fichiers/ : Images, PDF, ...
 - _layouts/ : Gabarit HTML
 - less/ : Feuilles de style Less
 - css/ : CSS généré via Less, ne pas toucher
 - _site/ : Fichiers statiques générés par Jekyll, ne pas toucher

## Feuilles de style

Les feuilles de style sont pré-processées avec [Less](http://lesscss.org/).

Les fichiers package.json et brunch-config.js, à la racine, permettent d'installer et d'utiliser [Brunch](http://brunch.io/) pour transformer le Less en CSS.

    brunch w

## Participer

 - [Pull requests](https://help.github.com/articles/using-pull-requests/)
 - [Format des commits](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md#commit)
