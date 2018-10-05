# Les différents types de composants

Un composant est un peu comme une fonction, il génère une réponse/code/return à chaque appel. Il existe deux grandes catégories de composants.


## Les composants fonctionnels
* fonctionnalité limité
* fonctionne comme un tuyau -> donnée entrée et JSX out
* Utiliser pour présenter des données (pas vraiment pour du traitement)
* Facile à écrire


## Le composant à état (Class Component)
* Classe
* possédant obligatoirement une méthode render retournant du JSX
* Peut recevoir des props
* Possède un state représentant l’état interne du composant, modifiable en invoquant la fonction setState.
* Depuis peu, la méthode constructeur n'est plus obligatoire et le state peut être déclarer comme simple objet.


## Comparaison syntaxique

```JavaScript
const Koukou = ( ) =>{
  return <Text>koukou</Text>
}
```

```JavaScript
class Koukou extends Component {
  render(){
    return <Text>koukou</Text>;
  }
}
```

## Intérêts d'une architecture par composant
L'intérêt de cette architecture ne vient pas seulement de la modularisation du code mais d'un élément invisible de prime abord mais essentiel dans le fonctionnement de React, le [Virtual DOM](https://www.codecademy.com/articles/react-virtual-dom). Ce mécanisme permet d'actualiser uniquement les éléments du DOM qui ont été modifier à l'intérieur des composants au lieu de les recharger complètement. Ceci évite des manipulations superflues sur le DOM, déjà très lent au départ. Techniquement, le Virtual DOM est une copie du DOM en mémoire. Il intervient entre l'appel de la fonction et l'affichage à l'écran des données.

Faire un diagramme (CodeSchool)


Répondre clairement à 3 questions :

Qu'est-ce qu'un State :
* Contexte (Class)
* this (binding)
* super()
* constructor()
* Lifecycle

Qu'est-ce qu'une Promise ?
* C'est un object
* Les méthodes associées


## Bibliographie et sources
- [https://reactjs.org/docs/react-component.html#the-component-lifecycle](https://reactjs.org/docs/react-component.html#the-component-lifecycle)