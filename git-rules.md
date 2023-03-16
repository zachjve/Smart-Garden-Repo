Organisation du projet sur GitHub pour un groupe de 5 personnes en utilisant une branche principale, des branches de fonctionnalités et des forks.

#### Branche principale (`main`) 
Elle contiendra le code stable et fonctionnel.

#### Utiliser des forks
Un fork est une copie du dépôt d'origine dans le compte GitHub du contributeur. Les contributeurs travaillent sur leur fork, puis soumettent des pull requests pour proposer des modifications à intégrer dans le dépôt d'origine.

Pour créer son fork :

1. Se rendre sur l'organisation et cliquer sur le repo.
2. Cliquer sur fork en haut a gauche.
3. Créer un fork.

##### Mettre à jour le fork
OK

Dans votre fork :
##### Créer des branches de fonctionnalités
Chaque membre de l'équipe doit créer des branches de fonctionnalités pour développer de nouvelles fonctionnalités ou résoudre des problèmes spécifiques. Pour créer une nouvelle branche à partir de `main` :

Créer et basculer vers une nouvelle branche pour votre fonctionnalité (remplacer `<feature-branch>` par un nom descriptif pour votre branche) :

```bash
git checkout -b <feature-branch>
```

Pour verifier que vous êtes sur votre branch de fonctionnalitée :

```bash
git branch
```

Pour bien faire en sorte que la branche contient tout les MAJ du main  :

```bash
git merge main
```

###### Commencer à travailler votre fonctionnalitée sur la branch. 

Une fois que la branche est créé et contient toute les MAJ `travailler sur votre fonctionnalitée`. . . . . . . . . . >

Pendant que vous travailler vous devez faire vos add vos commit et push toujours sur la branche de fonctionnalitée en s'assurant de bien push vers la branche. 

Une fois le travail terminé et une fois que tout fonctionne sur la branche il faut `merge` votre branche avec votre `main` (du fork) pour cela :

1. Se replacer sur le `main` (du fork) 

```bash
git checkout main
```

2. Merge la branche sur la branche main, (remplacer `<feature-branch>` par un nom descriptif pour votre branche) :

```bash
git merge <feature-branch>
```





Il faut `push votre travail vers votre fork` pour tester que vos ajouts fonctionnent bien avec le code global pour ça il faut veiller à ce que votre fork contienne bien les derniers ajouts du repository de l'organisation.

Une fois le travail terminé il faut `merge` votre branch avec votre `main` (du fork) 




4.  **Gérer les pull requests :** Lorsque vous ou un membre de votre équipe avez terminé le travail sur une branche de fonctionnalité, créez une pull request pour proposer les modifications à intégrer dans la branche `main`. Les autres membres de l'équipe doivent passer en revue les modifications, discuter et éventuellement demander des ajustements avant de fusionner la pull request.
    
    a. Sur la page du dépôt GitHub, cliquez sur l'onglet "Pull requests". b. Cliquez sur "New pull request". c. Sélectionnez la branche `main` comme branche de base et votre branche de fonctionnalité comme branche de comparaison. d. Cliquez sur "Create pull request". e. Ajoutez un titre et une description détaillée pour votre pull request, puis cliquez sur "Create pull request".
    
5.  **Fusionner les pull requests et supprimer les branches de fonctionnalités :** Une fois qu'une pull request a été examinée et approuvée, elle peut être fusionnée dans la branche `main`. Après la fusion, vous pouvez supprimer la branche de fonctionnalité pour garder votre dépôt propre et bien organisé.
    

En suivant ces étapes, vous pourrez organiser efficacement votre projet GitHub en utilisant la branche principale, des branches de fonctionnalités et des forks pour les contributions externes.