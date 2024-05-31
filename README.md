
# Instructions pour Exécuter le Projet

- Copiez l'exécutable Projet_Sup'trading.exe et lancez le, celui-ci va extraire les fichiers du projet.

- Une fois dézippé, le notebook server s'ouvrira automatiquement dans votre navigateur par défaut. Vous pouvez alors exécuter les cellules et explorer les analyses et les résultats.

- Exécutez "CAC 40.ipynb" pour avoir l'historique des actions du CAC 40 qui génère deux fichier : csv et excel
```
Le fichier excel est envoyé a 17hh 30 par mail à l'utilisateur qui devra rentrer son mail dans cette section du code
```

- Exécutez ensuite "Prediction_CAC40_Stock.ipynb" pour voir les techniques de machine learning pour prédire les prix de clôture des actions du CAC 40.


## Fichiers Inclus
- `projet.bat` : S'exécute dès que le projet est décompressé.
- `Prediction_CAC40_Stock.ipynb` : Notebook principal contenant le code et les analyses.
- `CAC 40.ipynb` : Notebook principal contenant le code et les analyses.
- `requirements.txt` : Liste des packages nécessaires pour exécuter le notebook.



# Collecter les données des actions du CAC40 automatiquement
```
# Configurer le Planificateur de Tâches

### 1) Ouvrir le Planificateur de tâches :
- Ouvrez le Planificateur de tâches en recherchant "Planificateur de tâches" dans le menu Démarrer.

### 2) Créer une nouvelle tâche :
- Dans le Planificateur de tâches, cliquez sur "Créer une tâche" dans le volet de droite.

### 3) Onglet Général :

- Donnez un nom à votre tâche, par exemple, "Lancer Jupyter Notebook au démarrage".
- Choisissez "Exécuter uniquement si l'utilisateur est connecté".
- Cochez "Exécuter avec les autorisations maximales".
 
### 4) Onglet Déclencheurs :

- Cliquez sur "Nouveau" pour créer un nouveau déclencheur.
- Définissez le déclencheur sur "À l'ouverture de session".
- Choisissez "Tout utilisateur" si vous souhaitez que la tâche s'exécute lorsque n'importe quel utilisateur se connecte, ou "Utilisateur spécifique" pour qu'elle s'exécute pour un utilisateur particulier.
- Cliquez sur "OK".

### 5) Onglet Actions :

- Cliquez sur "Nouveau" pour créer une nouvelle action.
- Définissez l'action sur "Démarrer un programme".
- Parcourez l'emplacement de votre fichier run_notebook.bat et sélectionnez-le.
- Cliquez sur "OK".

### 6) Onglet Conditions :

- Décochez "Démarrer la tâche uniquement si l'ordinateur est alimenté par le courant secteur" pour vous assurer qu'elle s'exécute également sur batterie.
- Ajustez les autres conditions selon vos besoins.

### 7) Onglet Paramètres :

- Cochez "Autoriser l'exécution de la tâche à la demande".
- Assurez-vous que "Si la tâche échoue, redémarrer tous les" est coché, et définissez un intervalle (facultatif).

### 7) Terminer :

- Cliquez sur "OK" pour enregistrer votre tâche.
- Étape 3 : Vérifier la tâche
- Redémarrez votre ordinateur.
- Connectez-vous et vérifiez que les cellules de Jupyter Notebook s'exécutent automatiquement.
```

## Remarques
- Assurez-vous d'avoir `pip` et `Jupyter Notebook` installés sur votre système.
- Les versions des packages sont spécifiées dans le fichier `requirements.txt`. Si vous rencontrez des problèmes de compatibilité, essayez de mettre à jour les packages.

## Contact
Pour toute question ou commentaire, veuillez contacter l'auteur du projet.
