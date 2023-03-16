Organisation du projet sur GitHub pour un groupe de 5 personnes en utilisant une branche principale, des branches de fonctionnalités et des forks.

#### Branche principale (`main`) 
Elle contiendra le code stable et fonctionnel.

#### Utiliser des forks
Un fork est une copie du dépôt d'origine dans le compte GitHub du contributeur. Les contributeurs travaillent sur leur fork, puis soumettent des pull requests pour proposer des modifications à intégrer dans le dépôt d'origine.

Pour créer son fork :

1. 

Dans votre fork :
##### Créer des branches de fonctionnalités
Chaque membre de l'équipe doit créer des branches de fonctionnalités pour développer de nouvelles fonctionnalités ou résoudre des problèmes spécifiques. Pour créer une nouvelle branche à partir de `main` :

1. Mettez à jour votre dépôt local avec la dernière version de `main` :

```bash
git checkout main git pull origin main
```

2. Créez et basculez vers une nouvelle branche pour votre fonctionnalité (remplacer `<feature-branch>` par un nom descriptif pour votre branche) :

```bash
git checkout -b <feature-branch>
```

4.  **Gérer les pull requests :** Lorsque vous ou un membre de votre équipe avez terminé le travail sur une branche de fonctionnalité, créez une pull request pour proposer les modifications à intégrer dans la branche `main`. Les autres membres de l'équipe doivent passer en revue les modifications, discuter et éventuellement demander des ajustements avant de fusionner la pull request.
    
    a. Sur la page du dépôt GitHub, cliquez sur l'onglet "Pull requests". b. Cliquez sur "New pull request". c. Sélectionnez la branche `main` comme branche de base et votre branche de fonctionnalité comme branche de comparaison. d. Cliquez sur "Create pull request". e. Ajoutez un titre et une description détaillée pour votre pull request, puis cliquez sur "Create pull request".
    
5.  **Fusionner les pull requests et supprimer les branches de fonctionnalités :** Une fois qu'une pull request a été examinée et approuvée, elle peut être fusionnée dans la branche `main`. Après la fusion, vous pouvez supprimer la branche de fonctionnalité pour garder votre dépôt propre et bien organisé.
    

En suivant ces étapes, vous pourrez organiser efficacement votre projet GitHub en utilisant la branche principale, des branches de fonctionnalités et des forks pour les contributions externes.