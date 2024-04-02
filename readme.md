<h1 align=center> Lua Bath </h1>

## Introduction

Bienvenue au petit bain de Epitech ! Au plat du jour: Le **lua** !
[inserer le nombre d'heure] de pur plaisir où vous allez apprendre les
bases de la programation, avec le meilleur language du monde.

### Trigger Warning

Le lua est mon langage de coeur ❤️, alors appreciez ce petit bain car il est
merveilleux.

## Préparatifs

Votre voyage au pays du lua ne sera pas de tout repos. Tout d'abord, vous
allez regarder si le lua est installé sur votre machine.

### Le terminal

Mais avant, nous allons aller dans ce qu'on appelle un `terminal`. Comment
ouvrir un terminal ?

Si vous etes sur un ordinateur windows:
1. Appuyez sur la touche Windows.
2. Ecrivez `ubuntu`, et pressez la touche Entrer.

Si vous etes sur un autre truc, c'est que vous etes surement sur un ordinateur
linux:
1. Appuyez sur CTRL + ALT + T

Si ca ne marche pas:
1. Appuyez sur la touche Windows.
2. Ecrivez `terminal`, et pressez la touche Entrer.

### Le programme

Vous voici sur le terminal. C'est ce qui permet à vous, jeunes développeurs et
développeuses, de parler à votre machine pour lui ordonner des instructions.

L'une de ces instruction est celle de lancer le logiciel du lua. Mais nous
devons d'abord verifier que le programme est bel et bien installé sur votre
machine.

C'est pour cela que nous allons écrire la commande suivante
```sh
which lua
```
En gros on demande à votre ordinateur où se trouve le programme lua.

Si vous avez une reponse, c'est que votre ordinateur a trouvé le programme !

Sinon, vous allez devoir l'installer. Donc l'installation se fera également
sur votre terminal. Rappellez vous, c'est ce qui permet de parler à votre
machine, donc si vous avez besoin d'installer des applications, vous pouvez
egalement le faire sur votre terminal.

Pour cela, nous allons d'abord trouver ce qu'on appelle un `Package Manager`,
ou "Gestionnaire de paquets" 🥖🇫🇷 si vous voulez le dire en Français, même si
je trouve personnellement ça ridicule.

Pour cela, nous allons devoir encore utiliser la commande `which`.
```sh
which apt || which dnf || which brew
```

Normalement, il vous donnera le 

## Hello world !

Votre premiere tache sera d'afficher 

## Une pluie de Hello world ??

J'aime vraiment la phrase "Hello world", tellement que je veux que vous
me l'affichiez 100 fois.

Mais il y a un hic, vous n'avez le droit qu'à un seul print !

## J'aime l'alcool

Mais ai-je le droit d'en boire ? Oui, seulement si j'ai plus de 18 ans

Créez votre **variable** nommée `age`, et donnez lui un nombre.

Faites en sorte que votre programme affiche "Je peux boire de l'alcool !" si
l'age est plus que 18,
qu'il affiche "Joyeux anniversaire! Tiens, de la tequilla" si votre age est 18
et afficher "Pas d'alcool pour toi mon enfant" si l'age est en dessous de 18.

## Une averse de Hello world ????

Tout à l'heure, vous avez réussi à m'afficher "Hello world", 100 fois. Bravo !
Vous avez surement utilisé une boucle.

Maintenant, affcihez moi Hello World, 100 fois en utilisant 3 boucles
differentes.

## Ma premiere fonction: myIsNeg

Créez moi une fonction, qui s'appelle myIsNeg. Elle **renvoie** `true` si le
chiffre que je te donne en **paramettre** est negatif, et `false` si le
chiffre est positif.

> Qu'est ce qu'une fonction ?

> Ca veut dire quoi renvoyer (return) ?

> C'est quoi un paramettre ?

Voici un petit code pour vous aidez à savoir si vous avez bien reussi:
```lua
print(myIsNeg(-3)) -- true
print(myIsNeg(42)) -- false
```

## 1 + 1

Maintenant que vous avez créez votre premiere fonction, il est tant d'en faire
une deuxieme.

Créez votre propre fonction, myAdder, qui va prendre 2 arguments en
paramettres, qui sont deux nombres, et qui va renvoyer l'addition des deux
nombres.

Voici un petit programme qui devrait fonctionner avec votre fonction:
```lua
print(myAdder(1, 1)) -- 2
print(myAdder(3, 4)) -- 7
```

## Secure 1 + 1

Malheuresement, les gens ne sont pas tous gentils, certains vont vouloir
envoyer des chaines de characteres a la place de chiffre dans votre myAdder,
modifie ta fonction pour qu'elle n'accepte seulement des `nombres` en
paramettre.

```lua
print(myAdder(1, 1)) -- 2
print(myAdder(1, "hello")) -- nil
```

> Qu'est ce qu'un type ?

## A table !

En lua, il existe un type qui est primordial à la programmation. Ce sont les
tables, qui sont tres utiles pour tout et n'importe quoi.

Voici à quoi ressemble ma table:
```lua
local fruits = {"banana", "apple", "ananas", "banana"}
```

Ecris moi une fonction qui s'appelle `myPutTable` qui prends ma table en
paramettre et qui m'affiche son contenu.

Le code si dessous devrait marcher:
```lua
myPutTable(fruits) -- banana apple ananas banana
```

## Devinette

Je vais juste vous donner ce petit code, vous allez devoir ecrire le code
qui vous permet d'avoir une table donnant ce resultat:
```lua
local myDevinette = ... -- du code
... -- du code

print(myDevinette.number) --

myDevinette.hello("Foo") -- "Bonjour Foo !"
myDevinette.hello("Bar") -- "Bonjour Bar !"

myDevinette.add(4, 2) -- "4 + 2 = 6"
myDevinette.add(4, "hello") -- "4 + hello, je ne peux pas le faire"
myDevinette.add(1, 0) -- "1 + 0 = 1"
```

> Utilisez ce que vous avez appris avec votre adder !

## 1 + 1 + 1 ...

Moi, je veux vraiment pas ajouter seulement 2 nombres. J'aimerais bien en
ajouter, voyons voir... une infité ?

Ecris la fonction `mySuperAdder`, qui te permet de d'ajouter une infinité
de chiffre ensemble.

Le code ci dessous devrait fonctionner:
```lua
print(mySuperAdder(1, 2, 3, 4)) -- 10
print(mySuperAdder(3, 3)) -- 6
print(mySuperAdder(1)) -- 1
```

## Meta-verse

En lua, vous avez ce qui s'appelle des `metatables`. En gros, c'est ce qui
permet de donner des attributs en plus a vos tables.

## Cobblestone generator

