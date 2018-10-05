# let - const / var et le scope

Le scope est le contexte dans lequel est déclaré la variable.

- `var` est function scoped
- `let` et `const` sont block scoped  

## `var`
Les déclarations de variables sont traitées avant que le code soit exécuté, peu importe où elles sont placées dans le code. **La portée d'une variable déclarée avec `var` est le contexte d'exécution courant**, c'est-à-dire : la fonction qui contient la déclaration ou le contexte global si la variable est déclarée en dehors de toute fonction.

## `let`
`let` permet de déclarer des variables dont la portée est limitée à celle du bloc dans lequel elles sont déclarées. Le mot-clé `var`, quant à lui, permet de définir une variable globale ou locale à une fonction (sans distinction des blocs utilisés dans la fonction).

## `const` 
La déclaration `const` permet de créer une constante nommée accessible uniquement en lecture. Cela ne signifie pas que la valeur contenue est immuable, uniquement que l'identifiant ne peut pas être réaffecté. Autrement dit la valeur d'une constante ne peut pas être modifiée par des réaffectations ultérieures. Une constante ne peut pas être déclarée à nouveau.

***
   
### Remarques
On ne peut pas déclarer deux let identique à l'intérieur du même scope.

On ne peut pas changer l'entièreté d'une constante mais on peut en mettre à jour les propriétés.

Suivez la méthodologie suivante si vous avez du mal à dissocier les   let et puis refactoriser les let qui ne changeront pas en const


## 

- [https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Instructions#D%C3%A9clarations](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Instructions#D%C3%A9clarations)