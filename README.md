Commandes unix 
==============

* **`echo`** : Affiche une ligne de texte  
utilisation : `echo "bonjour"`
* **`man`** : retourne le mode d’emploi de la commande s’il existe.  
utilisation : `man echo`
* **`cd`** : permet de se déplacer dans le système de fichiers.  
utilisation : `cd repertoire`  
Pour revenir au répertoire parent, utilisez la commande comme ceci : `cd ..` (Le "`..`" représente le répertoire parent.
* **`ls`** : liste le contenu du répertoire courant.   
utilisation : `ls [options]`  
Vous pouvez également préciser un chemin pour lister le contenu de celui-ci :  
`ls repertoire`  
options :   
`-l` affichage sous forme de liste, avec plus d'informations  
`-a` affichage de tous les fichiers (même les fichiers cachés)
* **`pwd`** : affichage du répertoire courant  
utilisation : `pwd`
* **`mkdir`** : crée un répertoire  
utilisation : `mkdir nouveau_dossier`
* **`rmdir`** : Supprime un répertoire vide  
utilisation : `rmdir nouveau_dossier`
* **`cp`** : Copie un fichier  
utilisation : `cp fichier_a_copier destination`  
options :  
`-R` : Permet de copier le contenu d'un dossier
* **`mv`** : Déplace et/ou renomme un fichier   
utilisation : `mv source destination`
* **`rm`** : Supprime un fichier  
utilisation : `rm fichier`  
options :  
`-r` : permet d'effacter un dossier et son contenu (récursif)
* **`history`** : montre à l’utilisateur les dernières commandes utilisées.  
utilisation : `history [nombre]`
* **`touch`** : modifie les horaires des dernières modifications du fichier en les mettant à l’heure où la commande est appelée. Si le fichier passé en argument n’existe pas, le fichier est crée et est vide.  
utilisation : `touch fichier`
* **`cat`** : concatène des fichiers et affiche le résultat sur le terminal.  
utilisation : `cat test`
* **`ssh`** : Se connecte à distance à une autre machine.  
utilisation : `ssh nom_utilisateur@machine_distante`
* **`nano`** : Edition d'un fichier texte.  
utilisation : `nano fichier`