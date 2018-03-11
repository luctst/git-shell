# Création d'un repo pour découvrir la ligne de command git
Dans ce fichier on va découvrir comment utiliser git pour versioner son code, travailler à plusieurs etc... On va également utiliser le remote [GitHub](https://github.com) qui permet de stocker son repository déclarer des issues..

## git init
```
Repo git init
```
Cette commande va tout simplement nous permettre d'installer git dans notre projet afin de pouvoir utiliser les lignes de commandes git par la suite.

## git status
```
Repo git status
```
Cette commande va nous renvoyer l'état de nos fichiers c'est-à-dire si un ou plusieurs fichiers a été crées, subis des modifications etc.. qu'il faudra si changements il y a commit afin de créer une version unique des changements.

## git add
```
Repo git add nomDuFichier
```
Cette commande indique à git qu'il faut surveiller ce fichier si il subit des changements alors git sera qu'il a été modifé et pourra ainsi le versioner.

## git commit
```
Repo git commit [-a -m] "Entrez votre message"
```
Cette commande est l'une des plus importante elle permet à git de créer une version unique afin que le développeur puisse un jour si il le veut revenir à cette version du code, il est aussi important de définir un message avec l'option "-m". Si il faut à chaque fois de faire un commit traquer un fichier avec "git add" il est possible au moment du commit de fusioner les deux commandes afin de gagner en ajoutant les options "-a -m".

## git push
```
Repo git push origin master
```
Cette commande permet d'envoyer vos commits dans votre remote en l'occurence si votre code est sous GitHub(origin) dans votre branche master qui est votre branche principale la ou est déposé votre code.
