# recherche dans des fichiers, commande grep
1. Quelles sont les options de grep qui permettent d’obtenir des lignes de contexte (qui précèdent t/ou suivent la ligne où figure le mot) ?
2. Comment faire apparaître le numéro de la ligne où figure le mot recherché ? Que se passe-t-il quand on demande également des lignes de contexte ?
3. Comment faire pour afficher le nombre d’occurences du mot recherché ?
4. Comment faire pour que grep ignore la casse des caractères (différence entre majuscules et minuscules) dans sa recherche ?
5. Comment faire pour faire apparaître non pas les lignes où figurent le mot, mais les noms des fichiers ?
6. Comment faire apparaître les lignes où ne figurent pas le mot recherché ?
7. Comment faire apparaître les noms des fichiers ne contenant pas le mot recherché ?
8. Comment faire pour que grep ne recherche que les lignes où figure le mot tel quel, et non pas ses variantes ? Par exemple : on cherche le mot «travail», mais pas «travailleur» ou «travailler».
9. Comment faire pour chercher plusieurs mots à la fois en faisant apparaître les numéros des lignes ?
10. Chercher toutes les lignes commençant par «a» ou «A».
11. Chercher toutes les lignes finissant par «rs».
12. Chercher toutes les lignes contenant au moins un chiffre.
13. Chercher toutes les lignes commençant par une majuscule.
14. Chercher toutes les lignes commençant par «B», «E» ou «Q».
15. Chercher toutes les lignes finissant par un point d’exclamation.
16. Chercher toutes les lignes ne finissant pas par un signe de ponctuation (point, virgule, point- virgule, deux-points, point d’interrogation, point d’exclamation).
17. Chercher tous les mots contenant un «r» précédé de n’importe quelle lettre majuscule ou mi- nuscule.
18. Chercher tous les mots dont la seconde lettre est un «r».

#  les commandes head et tail
1. Affichez les 15 premières lignes du fichier /etc/hosts, les 15 dernières lignes, toutes les lignes à partir de la quinzième, les lignes 15 à 20.
2. Récupérer les lignes 5 à 9 d’un fichier de 12 lignes.
3. Comment afficher la cinquième ligne d’un fichier ?

# droits d’accès, liens
1. Changez les droits d’un fichier fic1 pour que tous ceux de votre groupe puissent écrire de- dans.
2. Donnez en une seule ligne le droit d’exécution à tous les utilisateurs d’un fichier script qui n’a jusqu’alors que des droits standards (-rw-r–r–).
3. Lefichiertotoalesdroitssuivants:-rwxr–r–.Modifiez-enlesdroitsenunelignedecommande de sorte que le propriétaire n’ait plus que le droit de lecture.
4. Modifier les droits du fichier toto (-rwxr–r–) de sorte que le groupe et les autres utilisateurs aient les mêmes droits que le propriétaire.
5. Quelle option permet de modifier récursivement les droits d’un répertoire et des fichiers qu’il contient ?
6. Quelle option de mkdir permet de créer un répertoire en spécifiant les droits sur ce répertoire ?
7. Affichez et interprétez les droits de /usr/games/.
8. Vous avez chez vous un répertoire tmp/ qui contient un fichier bidon. Créez un lien physique sur tmp/bidon appelé blo, dans votre répertoire d’accueil (HOME). Comparez les contenus de tmp/bidon et de blo. Que contient blo ?
9. Même question avec un lien symbolique.
10. Quelles sont les différences entre les liens durs et les liens symboliques ?
11. Dans quel cas ne peut-on pas faire de lien physique ? Que faut-il faire ?
12. Quel est l’effet de chmod sur un lien ? 
