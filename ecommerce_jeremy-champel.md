Q1: Quelle est la différence entre un fork et un clone ?

Un fork permet de copier un repertoire dans notre espace personnel. On peut donc travailler 
sur le repertoire directement sur notre profil et pas impacter le repertoire de base qui est 
possiblement sur un autre profil.

Un clone, lui permet de copier en local le repertoire sans le tranferer dans notre espace 
personnel. Donc lors de d'une modification, celle-ci ce fera sur le repertoire de base,
elle sera donc visible à tout ce qui on acces au repertoire de base et modifira le repertoire
de base


Q2: Github propose un clone ou download ( bouton vert ), quelle est la différence fondamentale entre les deux ?

En "download" le fichier, nous avons simplement tous les fichiers source sans .git, nous n'avons donc pas le dépôt. 
Lorsqu'on clone, on obtient une copie de l'historique et c'est un dépôt git fonctionnel.


Q3: Quelle est la commande git permettant de visualiser l'historique du projet ?

git log


Q4: Chaque commit a un numéro unique, seriez vous retrouver celui du cinquième commit de ce repository ?

5651629bb4da4aa2298339d7daa58247d25c4bf


Q5: D'ailleurs comment savoir, quel est le contenu de ce cinquième commit, c'est à dire quelles ont été les modifications apportées au projet au 3ième et 4ième commit 

git log --stat -p 5651629bb4da4aa2298339d7daa58247d25c4bf


Q6: Juste avant de commiter, quelle est la commande pour visualiser le contenu de son prochain commit ?

git status


Q7: Pourquoi la première personne peut partager ses changements sans problème et les autres sont obligées de faire une opération supplémentaire ?


Q9: Quelles sont les étapes pour résoudre des conflits sous git ?

Choisir le commit qu'on souhaite conserver en cliquant sur le bouton

Q10: Comment vous vous assurez que git n'est plus en état de conflit ?

Via un git status

Q11: Quel fichier a été modifié par le script ?

Le fichier modifieé est le script.js


Q12: Ecrasez les modifications faites sur ce fichier en utilisant git

git reset


Q13: Faire un git status, qu'observez vous ?

Il y a une nouvelle image => computer.jpeg. Ce fichier est "untracked"


Q14: NB: vous pouvez faire ça uniquement sur des commits non partagés. Pourquoi ?


Q15: Erreur script: Visualiser votre historique, que s'est t-il passé ?

Il y a eu 5 nouveaux commits

Comment revenir en arrière et donc ignorer les 5 derniers commits ?

git reset  --hard HEAD~5

NB: vous pouvez faire ça uniquement sur des commits non partagés. Pourquoi ?

Q16: Résumé en une phrase l'intérêt des branches :

Permet d'éviter d'avoir des conflits sur

Q17: Sans le savoir vous travaillez déjà avec des branches, quel est le nom de la branche par défaut de git ?

LA branche Master



