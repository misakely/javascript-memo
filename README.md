# javascript-memo

# Types de données

Une primitive

Est une valeur de type primitif.
Il existe 7 types primitifs : string, number, bigint, boolean, symbol, null et undefined.

Nombre

Créez un script qui invite le visiteur à entrer deux nombres, puis affiche leur somme.

let a = +prompt("Le premier numéro?", "");
let b = +prompt("Le second numéro?", "");

alert( a + b );

# Notez le plus unaire + avant le prompt. Il convertit immédiatement la valeur en nombre.