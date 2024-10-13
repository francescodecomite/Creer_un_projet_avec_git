# Creer_un_projet_avec_git
 ## Le but du jeu

### Faciliter l'écriture de la documentation et la maintenance des fichiers qui la compose. 
La partie la plus difficile dans un projet, c'est sa diffusion, lorsqu'il est terminé ou en voie d'achèvement. 
On est bien content d'avoir fini, et passer du temps sur la doc, ce n'est pas le plus passionnant. Donc, autant 
rendre cette partie la plus simple et économe en travail. 

### Un projet et sa documentation évolutifs
On peut avoir envie de mettre en ligne une version provisoire qui sera susceptible d'être modifiée, 
soit par l'auteur du projet, soit à l'aide de suggestions des utilisateurs. 

### Faciliter l'accès
Troisième argument : rendre la description du projet accessible depuis n'importe où, sans avoir à passer par le site du Fabricarium, 
juste en diffusant l'adresse où est rangé le projet. 

### Indépendance par rapport au site du Fabricarium
Il m'est déjà arrivé de perdre toutes mes docs lors d'une refonte du site...

## Comment peut-on faire ? 
La solution que j'utilise est la suivante : 
* Je crée un dépôt GIT où j'entrepose mon projet. 
* Sur le site du Fabricarium, je crée un projet, dans la gallerie des projets, avec : 
    * Une photo
    * Un titre
    * Dans la description, je mets juste un lien vers le dépôt

Par exemple, ce [projet](https://fabricarium-fabmanager.polytech-lille.fr/#!/projects/martin-s-menace-un-puzzle-tres-enervant-a-decouper-au-laser)) sur le site
du Fabricarium correspond à la définition ci-dessus.

## Le principe
	GIT est un gestionnaire de versions. Il est normalement utilisé par des groupes de programmeurs qui travaillent ensemble sur un projet comportant de nombreux ficjhiers et répertoire. 

 	Les utilisateurs (en fait l'un d'entre eux), crée un *dépôt* : un endroit quelque part dans l'éther qui contiendra la dernière version courante du projet, ainsi que l'historique
de toutes les modifications et ajouts. L'administrateur peut inscrire d'autres membres avec des rôles qui peuvent légèrement différer, et les droits correspondants. 


 
## La démarche en pratique
1. ### Installer GIT sur sa/ses machines. 
	[Vous pouvez charger et installer GIT à partir de ce site](https://git-scm.com/downloads). C'est une bonne idée d'installer aussi une interface qui vous simplifie la vie, 
GIT vous en propose plusieurs. Personnellement, j'ai choisi Github sous Windows. 
2. ### Ouvrir un compte où vous pourrez stocker vos dépôts
