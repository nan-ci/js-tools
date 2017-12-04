# Le terminal

Le `terminal` vous permet d'exécuter des commandes et d'afficher leurs résultats sous forme de texte.
Vous pouvez l'ouvrir avec le raccourci `? + t`.

Vous pouvez faire beaucoup avec cette simple interface de texte. Apprendre à l'utiliser est important. Un grand nombre de programmes spécifiques n'ont pas d'interfaces utilisateur graphiques *(GUI)* et une simple interface de ligne de commande *(CLI)* est préférable à une mauvaise interface graphique.
 
Vos commandes sont exécutées à partir d'un répertoire, connu sous le nom de **répertoire de travail**.

Vous pouvez lister ce qui est dans votre répertoire de travail avec `ls` (list)
```sh
ls
```

Vous pouvez changer le répertoire de travail avec `cd` (Change Directory)
```sh
cd somedir # changer le répertoire de travail en 'somedir'
```

Vous pouvez afficher le répertoire de travail avec `pwd` (Print Working Directory)
```sh
pwd # afficher le répertoire de travail
```

Vous pouvez obtenir une brève description et quelques exemples simples de la plupart des commandes avec `tldr` (To Long Didn't Read)
```sh
tldr cd # afficher la page tldr de la commande cd
```

Si vous avez besoin de tous les détails, lisez le manuel en utilisant `man` (Manuel)
```sh
man cd # afficher la page de manuel de la commande cd
```
(comme vous pouvez le voir, le manuel est très détaillé, c'est pourquoi `tldr` est souvent suffisant)

Vous pouvez créer un nouveau répertoire avec `mkdir` (Make Directory)
```sh
mkdir somenewdir # créez un répertoire nommé somenewdir
```

*Autres commandes couramment utilisées `chmod`, `chown`, `ps`, `kill`, et plus!*

Il y a quelques caractères spéciaux pour les dossiers courants:
- `.` est le répertoire courant
- `...` est le répertoire parent
- `/` est le répertoire racine
- `~` est votre répertoire personnel d'utilisateur habituel (`/home/nom d'utilisateur/``)



# Git (Version Control System)
`git` est un système de contrôle de version, il est utilisé pour collaborer et partager des fichiers de code.

Il vous permet de gérer plusieurs versions d'un même projet, basculer entre eux, les fusionner et bien plus encore.

Il sert également de 'backup' et permet de revenir aux versions précédentes.

> Attention: notez que **github** n'est pas git, c'est une interface web et webhost
pour git, nous l'utilisons car il est gratuit pour l'open source, merci github :+1:

Commandes `git` les plus utiles:
```sh
git clone
git add
git commit
git push
git stash
```

Si vous voulez en savoir plus, consultez ce guide
[learngitbranching. js](https://learngitbranching.js.org/?demo)



# JavaScript (Langage de programmation)
`JavaScript`, souvent appelé `JS`, est une des technologies de base du web.
Au début, ce language était principalement utilisé pour rendre les pages Web interactives et fournir des programmes en ligne.

Il gagne en popularité à mesure que le Web grandit.

Les grandes entreprises (Google, Microsoft, Apple, Mozilla...) ont beaucoup investi sur le fait de rendre JavaScript rapide, en tant que tel, il est maintenant également utilisé pour de nombreuses plateformes y compris les mobiles (application Facebook), serveurs (PayPal), ordinateurs de bureau (Code by Microsoft)
et même les télévisions (Netflix).

C'est le premier language que nous aborderons puisque c'est l'un des plus populaires et est utilisable dans la plupart des [scénarios](https://www.youtube.com/watch?v=Q6TLWqqn82J4).

Pour d'autres références, voir [la documentation](https://developer.mozilla.org/bm/docs/Web/JavaScript)
*this will be your new bible*

# Node (système d'exécution)

`node` est utilisé pour exécuter vos fichiers JavaScript.

Node est ce qui a popularisé l'utilisation de JavaScript en dehors du web en lui donnant une api que vous pouvez utiliser pour interagir avec votre ordinateur, écrire des fichiers, créer des serveurs http et bien plus encore.

Pour en savoir plus, consultez la [documentation](https://nodejs.org/api/index.html)
*this will be your other bible*


```
tldr node
```



# NPM (Node Package Manager)

`npm` est le gestionnaire de paquet de node

Lorsque nous programmons, nous aimons partager et réutiliser des bouts de code entre les projets au lieu de tout recoder tout le temps.  
`npm` nous permet de faire cela en créant des 'package' de code que nous pouvons alors installer et utiliser dans nos autres fichiers JavaScript.

```
tldr npm
```

# Code (éditeur de code)

`code` est votre éditeur de code source par défaut

Vous pouvez ouvrir des fichiers depuis le terminal avec la commande `code`.

```sh
tldr code
```

L'écriture de code sera votre occupation principale, soyez à l'aise avec votre éditeur.

**Apprenez les raccourcis.**

C'est un outil puissant avec beaucoup de fonctionnalités, explorez-les et partagez à vos pairs vos supers découvertes.
