### Des notion de html
1. HTML
Hypertext Markup language (language de balise hypertexte)

=> un fichier `html` c'est d'abord du texte
=> il est ecris par un developeur (avec VS code par exemple)
=> il est vu par un utilisateur (avec Firefox par exemple )

Une balise html s'ecris: `<mabalise></mabalise>`

**Ex.** `<h1></h1>`

le texte s'ecrit entre balise.**

**ex.** `<h1> mon texte </h1>`

Il existe aussi des balise orphelines:
`<!DOCTYPE html> , <br> , <img> .....`

reference mozzila [https://developer.mozilla.org/fr/docs/Web/HTML/Reference/Elements](https://developer.mozilla.org/fr/docs/Web/HTML/Reference/Elements)

une balise ouvrante peut contenir un attribut nottamet `class=""`:
`<h1 class="maclasse"></h1>`
quelque balise importante
<h1></h1> por faire des titre
<p></p> pour faire des paragraphe
`<a href=""></a>` pour faire des liens
`<ul></ul>` pour faire des liste sans ordre
`<ol></ol>` pour faire des liste avec ordre
<li></li> por faire des item dans les liste
<img src=""> por ajouter une image
pour trouver le chemin vers un fichier on peut regarder: 
-dans le dossier courant avec ./
-dans un dossier exterieur avec ../


2. CSS

cascading style sheet: page de style en cascade

on peut ecrire du CSS:
-directement dans le fichier html entre les balise `<style></style>`
-dans un fichier `.css`

pour ecrire du css il faut un selecteru (nom d'une balise ou de class) des accolade des propriete des valeurs

```CSS
selecteur{propriete 1: valeur 1;
          propriete 2: valeur 2;
          ....
}
 Il existe plus de 500 propriete et encore davantage de valeur possible. cependant les valeur sont souvent : 
 -une couleur 
 - une taille