# Git

## Memo

* [les commandes de base](https://confluence.atlassian.com/bitbucketserver076/basic-git-commands-1026534676.html)
* [vidéos-tutos par point](https://egghead.io/lessons/misc-practical-git-create-local-repos-with-git-init)
---    
## Le concept

Git est un outil pour versionner un projet (de code souvent). 
Ce n'est pas un drive, c'est un outil qui surpasse les Ctrl+Z. [Voici une vidéo qui pourra bien introduire le sujet.](https://www.youtube.com/watch?v=hwP7WQkmECE) 
Dans le jargon git un projet = un repository. (un dossier dans lequel est stocké le code que tu veux versionner)  

### Github, Gitlab, Bitbucket... C'est quoi du coup ?

Les 3 plateformes font exactement la même chose: Elles gardent ton projet git en ligne. Tu as donc un repo(sitory) en ligne et un autre en "local" (sur ton ordi). les 2 repos ne sont pas automatiquement synchronisés (il faut passer une commande "push"). Pourquoi le mettre en ligne ? Pour pouvoir bosser à plusieurs ! Et pourquoi ne pas synchro les repos locaux et en ligne automatiquement ? Pour permettre à tout le monde de changer la même partie de code en même temps. Quand les repos de chacun seront synchronisés, on choisira ce que l'on garde dans le git en ligne. 
Github est la plateforme la plus utilisée, elle est gratuite et est accessible depuis tout ordinateur ayant une connexion internet.  
Gitlab et Bitbucket servent pour les entreprises/ organisations. La version d'essai seulement est gratuite mais cela permet d'avoir un outil bien plus sécurisé.


### Les actions

Quand c'est déjà bien expliqué quelque part, pourquoi se priver ?  
[Toutes les actions de base expliquées](https://dev.to/stefant123/basic-git-commands-explained-1cjd)

### Les petits concepts qui font de grand changements
    
* un commit = un changement, c'est la merde sinon pour retrouver oú est ce que un changement a été fait
* un commit = un message CLAIR. Même raison qu'au dessus.
* une branche = un seul objectif, sinon si on veut garder une partie mais pas l'autre c'est beaucoup plus compliqué (cherry picking et rebase).
* un repo = une "git branching strategy", sinon on s'emmêle les pinceaux
---     
## Tutos/Vidéos/Autres Sources

* [Un jeu vidéo pour apprendre Git](https://ohmygit.org/)
* [15 min pour prendre en main Git](https://www.youtube.com/watch?v=USjZcfj8yxE)
 
    
---      
## Pour être un pro
* [45 min pour avoir des standards pro](https://www.youtube.com/watch?v=Uszj_k0DGsg)
* [Quelques "git branching strategies"](https://www.flagship.io/git-branching-strategies/)(Des stratégies de management de code)
---
