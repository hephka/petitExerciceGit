# monPremierGit
Notre premier Git !

**BASH & GIT** 

- **BASH** est interpréteur en ligne de commande.
- **GIT** est un logiciel de gestion de versions décentralisé.

## Introduction Bash Shell


Bash pour [Bourne-Again shell](https://fr.wikipedia.org/wiki/Bourne-Again_shell).

L'un de vos meilleurs amis pour "Basher" sera l'option `--help` ! 


### Liste des commandes de base

`CTRL, ALT + T` pour ouvrir le terminal.

`pwd` pour Print Working Directory.

`cd` pour Change Directory.

`mkdir` pour Make Directory.

`ls` `l` pour List Short.

`clear` pour nettoyer votre terminal.

`nano` pour éditer du texte dans votre terminal.

`sudo` pour utiliser les droits du super-utilisateur.

`su` pour Switch User.

`apt-get` apt pour Advanced Packaging Tool, ici get permet la récupération du package | `brew` équivalent pour MAC.

`apt-cache` ici cache permet d'interroger le cache du package.

`chown` pour Change Owner. (nous reviendrons sur cette notion dans un second cours à ce sujet)

`chmod` pour Change Mode. (nous reviendrons sur cette notion dans un second cours à ce sujet)

`cp` pour Copy.

`rm` pour Remove.

`mv` pour Move.


### Les options de List Short

`--help` pour obtenir l'ensemble des paramètres.  

`-l` pour utiliser le format long d'affichage.  

`-r` pour inverser l'ordre d'affichage.


### Les commandes de base pour Nano

`CTRL + O` pour sauvegarder votre fichier.

`CTRL + X` pour quitter et enregistrer votre fichier.

`CTRL + G` pour obtenir de l'aide.


### Le statut Root

L'utilisateur root a un contrôle total sur votre machine.

Il dispose de tout les droits (lecture/écriture/exécution).


### Les paramètres d'apt-get

`apt-get install` pour installer un package.

`apt-get remove` pour désinstaller un package.

`sudo apt-get` pour utiliser apt-get avec les droits de super-utilisateur.

`--help` pour obtenir l'ensemble des paramètres.


### Les paramètres d'apt-cache

`apt-cache search` pour rechercher un package.

`apt-cache policy` pour afficher la version en vigueur.

`--help` pour obtenir l'ensemble des paramètres.



<br>

## Introduction Git

[Git](https://git-scm.com/) est un logiciel de gestion de versions décentralisé et il sera l'un de vos "meilleurs ennemis" pendant toute votre vie de développeur.se :)

N'oubliez pas que vous pouvez utiliser l'option `--help` à chacune des commandes git afin d'avoir plus d'informations.

### Listes des commandes de base vu en cours

`git config --global user.name votreNomOuPseudo` pour renseigner votre prénom ou votre pseudo.

`git config --global user.email votre@Email.com` pour renseigner votre email Github.

`git init` pour créer un nouveau dépôt.

`git status` pour afficher l'état de l'arborescence de travail.

`git add` pour ajouter le contenu d'un fichier à l'index.

`git commit -m "Votre message"` pour enregistrer les modifications dans le repository.

`git remote add origin https://github.com/VOTREPSEUDO/NOMDEVOTREREPO.git` pour gérer un ensemble de repositories suivis.

`git push -u origin master` pour mettre à jour les réfs distantes avec les objets associés par commit.

`git clone` pour cloner un dépôt distant.


### Petit exercice Git

1 - `git clone` de ce repository.

2 - créez un fichier avec votre NomPrénom.txt avec nano dans votre terminal dans votre copie locale de ce repository.

3 - écrivez "HelloWorld" dans ce document.

4 - `git add` de ce nouveau document.

5 - `git commit -m "votre message"` pour commit ce document.

6 - `git push -u origin master` de votre commit.

7 - ajouter le lien de votre git


