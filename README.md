# javascript-memo

# Créer un serveur http local avec nodejs

## liste des commandes utiles:
. npm init -y dans le dossier courant
. npm install lite-server --save-dev
. dans package.json editer la partie scripts et ajouter la ligne "server": "lite-server"
. creation d'un fichier bs-config.json auquel on pointera le rendu vers un dossier public (par exemple) 
{
    "server": {
        "baseDir": "./public"
    },
    "open": false
}
. creer du dossier public

# Types de données

Une primitive

Est une valeur de type primitif.
Il existe 7 types primitifs : string, number, bigint, boolean, symbol, null et undefined.

Nombre

Créez un script qui invite le visiteur à entrer deux nombres, puis affiche leur somme.

let a = +prompt("Le premier numéro?", "");
let b = +prompt("Le second numéro?", "");

alert( a + b );

## Notez le plus unaire + avant le prompt. Il convertit immédiatement la valeur en nombre.