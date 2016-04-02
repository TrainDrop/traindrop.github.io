# Fiches de Travaux Pratiques

Ce répertoire contient un ensemble de fiches pédagogiques destinées à l'enseignement du HTML, du CSS, le JavaScript (et pourquoi pas plus).

[Voir l'ensemble des fiches →](http://traindrop.github.io/fiches/)

## Contribuer une nouvelle fiche

Pour commencer une nouvelle fiche, vous devez passer par GitHub. Si vous êtes novice, une [petite lecture](http://articles.nissone.com/2014/11/gitpourlanulle/ "GitPourLaNulle sur le blog de Nissone") peut vous aider. Voici les étapes à suivre :

* réaliser un *fork* de ce dépôt sur votre compte GitHub ;
* cloner ce dépôt en local sur votre poste :
```
https://github.com/{votre pseudo}/fiches.git
```
* Au sein de votre dépôt GitHub local, travailler dans la branche ```master```
 * Soit via votre gestionnaire graphique
 * Soit en ligne de commande :
```CLIPS
git checkout master
```
* au sein du dossier ```_new```, ajoutez votre nouvelle fiche dans un dossier reprenant votre pseudo GitHub (et éventuellement, un numéro). Vous pouvez éventuellement copier/coller le dossier ```pseudoGitHub_001``` pour démarrer rapidement avec une mise-en-page type.

Une fois votre fiche écrite, vous pouvez la contribuer en faisant une *Pull Request*. L'équipe de TrainDrop s'occupera de l'intégrer au bon endroit. N'oubliez pas de bien renseigner le titre de votre fiche et les metadonnées "Principes abordés" et "Niveau requis", c'est ce qui servira aux lecteurs à la retrouver dans l'[index](http://traindrop.github.io/fiches/).

Evidemment, si vous avez des idées pour améliorer ce processus de contribution, n'hésitez pas à nous en faire part [dans le ticket dédié](https://github.com/TrainDrop/fiches/issues/1).

## Bonnes pratiques de mise en forme

Pour aider les développeurs et contributeurs à définir et maintenir des styles de codage cohérents en dépit de leurs différents éditeurs de texte ou IDE, TrainDrop utilise [EditorConfig](http://editorconfig.org/). Le fichier de configuration, situé à la racine du projet, définit quelques règles qui seront automatiquement appliquées par votre outil si vous l'équipez du plugin adapté.

Des plugins existent pour pour de nombreux outils, n'hésitez pas à [télécharger et installer celui ou ceux qu'il vous faut](http://editorconfig.org/#download "Télécharger un plugin EditorConfig").


