     TP1 - Maîtrise de Git

Partie 1 : Préparation de l'environnement Git

4/Cela affichera toutes les configurations globales, y compris votre nom d'utilisateur et votre adresse e-mail 
git config --global --list
Pour modifier votre adresse e-mail :
git config --global user.email "votre_nouvelle_adresse@example.com"

5/Modifier l'adresse e-mail pour le projet actuel :
git config user.email "votre.email@example.com"

Partie 2: Création d'un nouveau projet
6/
git add README.md
git commit -m "Ajout du fichier README.md"

7/
git remote add origin <url-du-depot>
git push -u origin master

Partie 3 : Concepts de base de Git

3/git checkout -- nom_du_fichier

4/git status

Partie 4 : Collaborer sur Git
4/
Cloner le dépôt distant :
git clone <url_du_dépôt>
Vérifier les branches distantes : 
git branch -r
Récupérer toutes les branches : 
git fetch --all

5/ git branch -d nom_de_la_branche

Partie 5 : Rebase d'une branche sur ‘master’

8/git rebase --abort

9/git log --oneline --no-merges HEAD..BRANCHE_CIBLE

Partie 6 : Uilisation de Gitflow

8/git branch
9/git flow hotfix delete mon-correctif

