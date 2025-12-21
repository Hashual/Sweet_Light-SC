# Sweet_Light-SC

## Mise en place du projet en local
### Avec gitHub Desktop
Depuis le menu de l'application, aller dans l'onglet cloner.
Renseigner l'URL suivant dans le champ demandant l'URL du repo à cloner.
```bash
https://github.com/Hashual/Sweet_Light-SC.git
```
Le projet est ensuite téléchargé en local, il ne reste plus qu'à l'ouvrir dans SweetLight depuis la section ouvrir un projet accessible par l'onglet file

### Depuis l'invite de commande git
Télécharger l'invite de commande git depuis ce lien
```bash
https://git-scm.com/
```
Ouvrir l'invite dans le dossier de son choix depuis le menu clic droit.
Attention, on clone le projet dans le dossier d'ouverture de la console git.
On clone le projet avec la commande
```bash
git clone https://github.com/Hashual/Sweet_Light-SC.git
```
Ensuite depuis sweetLight, ouvrir le dossier grâce à la section ouvrir un projet accessible depuis l'onglet file.

## Utilisation de git pour historiser ses modifications
### Explication
Git est ce qu'on appel un versionneur de projet en ligne. C'est à dire qu'il permet à différente personnes de travailler sur le même projet sans soucis.
Pour cela on créer ce qu'on appel des commits. Un commit, c'est une modification d'un ou plusieurs fichier qu'on veut pousser sur le cloud.
Ils permettent d'avoir une trace, un historique de toutes les modifications et de pouvoir revenir à une modification précédente.
Sauf si deux personnes modifient le même fichier en même temps il n'y pas de problème, c'est ce qu'on appel un conflit.

### Comment commit
Avant chaque commit, on télécharge(pull) par précaution pour récupérer les modifications des autres et ne pas provoquer de conflits.
Depuis github desktop, on peut voir d'afficher les "changes" sur les "unstaged files", ce sont les changements sur les fichiers impactés.
On va allors passer les fichiers en "staged files" puis indiquer un message de commit explicite du style :
```bash
Ajout [LYRES toutes] : mouvement en forme de X
```
On pousse(push) cette modification et l'autre personne peut la récupérer en faisant un pull.
