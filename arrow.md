# Arrow function
Une expression de fonction fléchée (arrow function en anglais) permet d'avoir une syntaxe plus courte que les expressions de fonction et ne possède pas ses propres valeurs pour `this`, `arguments`, `super`, ou `new.target`. Les fonctions fléchées sont souvent anonymes et ne sont pas destinées à être utilisées pour déclarer des méthodes.

## `this`

la valeur de `this` n'est pas passée dans l'arrow function. `This` prend le scope du parent.



***
### remarques 
- Elles sont presque toujours anonymes : `() => {}`
- Le return implicite (pas besoin de le mettre s'il retourne ...)
- Très utile lorsqu'on utilise un `setTimeout()`


- Dans l'animation en deux étapes il démontre la portée d'un this à l'intérieur et qu'avec un `setTimeout` normal on ne peut pas récupérer la portée du this à l'intérieur de la fonction imbriquée, il faut donc transformer le setTimeout en arrow function
- il donne un tip pour inverser deux valeurs (8min00) (wes bos)

default function argument : il est possible de passer des arguments avec une valeur par défaut pour éviter des erreurs.