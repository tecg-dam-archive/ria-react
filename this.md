# This

En JavaScript, le mot-clé `this` se comporte légèrement différemment des autres langages de programmation. Son comportement variera également légèrement selon qu'on utilise le mode strict ou le mode non-strict.

Dans la plupart des cas, **la valeur de this sera déterminée à partir de la façon dont une fonction est appelée**. Il n'est pas possible de lui affecter une valeur lors de l'exécution et sa valeur peut être différente à chaque fois que la fonction est appelée. La méthode `bind` a été introduite avec ECMAScript 5 pour définir la valeur de this pour une fonction, indépendamment de la façon dont elle est appelée. ECMAScript 2015 (ES6) a ajouté les [fonctions fléchées](./arrow.md) dans lesquelles this correspond à la valeur du contexte englobant.

## bind
La fonction (méthode) `bind()` crée une nouvelle fonction qui, lorsqu'elle est appelée, a pour contexte this la valeur passée en paramètre et éventuellement une suite d'arguments qui précéderont ceux fournis à l'appel de la fonction créée.