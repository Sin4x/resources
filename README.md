# javascript-selected-libraries

## Common

### [Fetch](https://developer.mozilla.org/fr/docs/Web/API/Fetch_API)
+ \+ standard ES 6
+ \+ Fonctionne avec des promesses 

### [Moment](http://momentjs.com/)
+ Librairie pour gérer les dates
+ Moment-timezone ajoute la gestion de la zone.

### [lodash](https://lodash.com/)
+ Peu utilisé, la plupart des fonctions sont présentes dans ES6

### [Highcharts](https://www.highcharts.com/)
+ Librairie pour faire les rendus de graphiques

### [Swiper](http://idangero.us/swiper/)
+ Librairie pour créer toute sorte de carousel.


## Angular JS
### [Angular-swiper](https://github.com/ksachdeva/angular-swiper)
+ cf swiper

### ng-translate
+ Traductions

### ng-resource
+ Utile avant Fetch

### angular-material
+ Implémentation material design de bonne qualité

### angular-bootstrap
+ Utilisation des composants bootstrap

## Angular ( > v2)
### [Ngrx-store](https://github.com/ngrx/platform)
+ Implémentation de Flux pour Angular
+ Y-a-t-il un équivalent à Redux-SAGA ?



## React
### [Redux](http://redux.js.org/)
+ Implémentation de Flux pour React
+ Pour créer un store ; découpler les données de leur affichage.
+ Evite de passage de données et callback entre les composants.
+ Avec Redux-SAGA ou avec Redux-thunk ?
+ Attention à bien découper les composants en 2 types : "presentational" / "container"

### [Material-ui](https://github.com/callemall/material-ui)
+ *À ne pas utiliser* car le code généré n'est pas propre et pas entièrement customisable.


### [Isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch)
+ Y-a-t-il un intérêt par rapport à Fetch ?

### [React-bootstrap](https://react-bootstrap.github.io/)
+ A voir ce que ça vaut ?

## Vue
### [Vuex](https://github.com/vuejs/vuex)
+ Implémentation de Flux pour Vue
+ Y-a-t-il un équivalent à Redux-SAGA ?

### [Vue-resource](https://github.com/pagekit/vue-resource)
+ Y-a-t-il un intérêt par rapport à Fetch ?



## [JQuery](https://jquery.com/)
Nothing, I loved you, but it's 2017 and I can't make SPAs with you.