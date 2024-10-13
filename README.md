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

GIT est un gestionnaire de versions. Il est normalement utilisé par des groupes de programmeurs qui travaillent ensemble sur un projet comportant de nombreux fichiers et répertoire. 

Quand un collaborateur décide de travailler sur le projet, il va chercher dans le dépôt la version courante à jour du projet, qui est alors chargée sur son ordinateur. Lorsqu'il a fini ses ajouts et modifications, il renvoie les fichiers sur le dépôt. Git vérifie alors qu'il n'y a pas de conflit entre les versions travaillées par plusieurs collaborateurs. Si c'est le cas, il prévient les utilisateurs, à eux de régler le conflit. Mais en fait on s'en moque, puisque dans notre cas, on est seul utilisateur. 

Git permet ausi de gérer les versions, de revenir en arrière, de créer des branches, en développant plusieurs versions en parallèle et en regroupant ces versions lorsqu'on le désire. Mais pareillement, ceci ne nous concerne pas. 

 Les utilisateurs (en fait l'un d'entre eux), crée un *dépôt* : un endroit quelque part dans l'éther qui contiendra la dernière version courante du projet, ainsi que l'historique
de toutes les modifications et ajouts. L'administrateur peut inscrire d'autres membres avec des rôles qui peuvent légèrement différer, et les droits correspondants. 


 
## La démarche en pratique
1. ### Installer GIT sur sa/ses machines. 
	[Vous pouvez charger et installer GIT à partir de ce site](https://git-scm.com/downloads). C'est une bonne idée d'installer aussi une interface qui vous simplifie la vie, 
GIT vous en propose plusieurs. Personnellement, j'ai choisi Github sous Windows. 
2. ### Ouvrir un compte où vous pourrez stocker vos dépôts


Une fois que vous avez ouvert GITHUB, choisissez File>Options>Accounts et ouvrez un compte chez Github.com. A vous de voir comment ça se passe avec d'autres interfaces (il en existe peut-être une
sur les serveurs de l'Université. En fait, non); 
