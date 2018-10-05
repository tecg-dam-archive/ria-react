# Object

Les objets en JavaScript sont des collections de paires de **noms** (chaînes) et de **valeurs** (toutes valeurs) où le nom est séparé de la valeur par deux points (:)


## Method
Une fonction dans un objet est une méthode de l'objet.

  ```javascript
  const person{
    firstElement:'coucou',
    methodOld:function(){},
    methodNew(){},
    fourthElement: 'blabla'
  }
  ```

Pour accéder une propriété d'un object :


## Destructuring
L'affectation par décomposition (destructuring en anglais) est une expression JavaScript qui permet d'extraire (unpack en anglais) des données d'un tableau ou d'un objet grâce à une syntaxe dont la forme ressemble à la structure du tableau ou de l'objet.

La syntaxe pour décomposer un objet est assez simple : `const objectDecomp = { param1, param2, ...}`


Il est également possible de renommer en déstructurant : `const {param1:new_name, param2, ...} =`

Enfin, il est possible de créer des fallbacks pour les valeurs manquantes :

  ```javascript
  const settings = { width: 300, color: black,}
  const {with = 100, height = 100, color = blue, fontSize = 25} = settings;
  ```

## Bibliographie et sources

* [https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Op%C3%A9rateurs/Affecter_par_d%C3%A9composition](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Op%C3%A9rateurs/Affecter_par_d%C3%A9composition)
* [https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/Object](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Objets_globaux/Object)