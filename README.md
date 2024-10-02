# Cadriciel_depart_La_Pasteque
Structure de développement standard des cours de RPNI 1-2-3-4, spécialement préparer pour le projet 2 de RPNI 3.

On se réunis d'abord en équipe;
Chaque équipe doit créer un compte d'équipe sur GitHub et tout les équipiers doivent y être invités. Note: Il est possible aussi que le dépôt soit héberger dans l'un de vos comptes de membre;
Création du dépôt du La_pastèque dans le compte sur GitHub. Ajouter le ReadMe (pas de .gitignore)
Un membre de l'équipe clone le projet depuis GitHub dans son dossier Site\rpni3\
Le même membre glisse/dépose le cadriciel distribué dans le répertoire créer en local
Dans la ligne de commande:
add . | commit -m  "commit initial" | push (ce qui distribuera le cadriciel aux membres de l'équipe en le poussant sur Git)
Les autres membres de l'équipe clonent le projet depuis GitHub dans leur dossier Site\rpni3\
Pour chaque étudiants, dans le terminal positionné dans le dossier racine du projet, faire l'installation de normalize avec npm:
npm install normalize.scss --save-dev
Dans phpmyadmin du serveur local de chaque membre de l'équipe, faire l'installation du fichier ressources/SQL/24_rpni3_lapasteque.sql.
ATTENTION ICI!!! Utilisez le même nom de BD, le même utilisateur et le même mot de passe, sinon, on cours droit vers des conflits avec le ficher de connexion qui sera versionné.
Faire le test en affichant la page d'accueil. Si tout fonctionne bien, vous devriez être en mesure de voir première page.
Un fois toute ces étapes effectuées ce sera un laboratoire pour faire avancer votre design.
