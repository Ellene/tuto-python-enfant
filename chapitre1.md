Chapitre 1 : Ecrire et exécuter des instructions à partir d'un fichier
=======

Pour écrire des instructions plus complexes, nous allons utiliser un fichier. 
Tu peux en créer un et son nom doit obligatoirement finir par `.py` on appelle ça une extension.
Si tu crées un fichier qui s'appelle `code.py`, tu devras ensuite l'exécuter comme ceci :
```
python code.py
```
Pour le moment, il n'exécutera rien car ton fichier est vide. Mais patience, on y arrive.

Les instructions sont une ou plusieurs lignes que tu vas écrire pour dire à python ce qu'il doit faire.

Les assignations
-----------
Les assignations permettent de donner une valeur à une variable.  
On peut lui donner une valeur simple comme un `int` ou un `string` :
```python
age = 10
pikachu = "pika"
```
tu peux aussi changer plusieurs fois la valeur de ta variable dans ton code :
```python
pikachu = "pika"
print(pikachu)
pikachu = "chu"
print(pikachu)
```
Ce code va t'afficher `pika` puis `chu`
ou un calcul :
```python
age = 2023 - 2013
```
Les opérateurs
-----------
Il est possible de faire différents calculs avec python grâce aux opérateurs.
  - les calculs mathématiques sur les `int` et les `float` : `+`, `-`, `*` (pour la multiplication), `/` (division), `<` (strictement infèrieur), `>` (strictement supèrieur), `<=` (inférieur ou égal), `=>` (supèrieur ou égal),`==` (égal) 
  - l'opérateur pour les `int` uniquement : `%' (modulo qui permet de connaître le reste sur une division)
  - on peut utiliser le `+` sur le string cela par assembler 2 chaînes de caractères par exemple `"pika"+"chu"` va retourner `"pikachu"`  
  
Les instructions `if`
-----------
Pour écrire une condition il faut utiliser le `if`. La condition permet d'exécuter du code uniquement dans certains cas. Et attention il faut bien faire attention aux espaces (tu peux utiliser 4 espaces ou la touche tab)  pour que python comprenne l'instruction. Ces espaces sont appelés *indentation* en informatique.
```python
nombreBoulesCristal = 7
if nombreBoulesCristal == 7:
    print("Je suis Sheron le dragon, je vais exaucer ton voeux")
print("Fin")
```
Dans ce code, on affiche le message 
```
Je suis Sheron le dragon, je vais exaucer ton voeux
Fin
``` 
puisqu'on on a le bon nombre de boules de cristal c'est-à-dire 7. 
Si `nombreBoulesCristal` était égal à 6 on aurait affiché 
```
Fin
``` 
On peut mettre plusieurs instrusctions dans le `if` mais il ne faut pas oublier l'indentation (c'est-dire les espaces) avant chaque ligne.
```python
jour = "jeudi"
if jour == "jeudi":
    print("matin : ecole")
    print("midi : cantine")
    print("apres-midi : ecole")
    print("soir : capoeira")
```
Ce code affichera donc
```
matin : ecole
midi : cantine
apres-midi : ecole
soir : capoeira
```

Les instructions `if else`
-----------
On a vu juste avant le `if` voyons maintenant le `if else` qui permet d'exécuter un autre code si les conditions dans le if ne sont pas respectées.
```python
nombreBoulesCristal = 6;
if nombreBoulesCristal == 7:
    print("Je suis Sheron le dragon, je vais exaucer ton voeux")
else:
    print("Sangoku continue de chercher les boules de cristal")
print("Fin")
```
Dans notre cas comme nombreBoulesCristal vaut 6 on va afficher :
```
Sangoku continue de chercher les boules de cristal
Fin
```

A ton tour
-----------
Avec ce que tu viens d'apprendre :
* [ ] Crée un fichier qui te permettra d'afficher `Salut`
* [ ] Crée une variable `pokemon` qui a pour valeur le nom de ton pokémon préféré

