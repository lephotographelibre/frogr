# frogr
This is a test for using github
the real Frogr application  by Mario Sánchez is available from: git clone git://git.gnome.org/frogr
 

Frogr is a small application for the GNOME desktop that allows users to manage their accounts in the Flickr image hosting website. It supports all the basic Flickr features, including uploading pictures, adding descriptions, setting tags and managing sets and groups pools.

1 récuperation des sources du produit http://ftp.acc.umu.se/pub/GNOME/sources/frogr/0.11/frogr-0.11.tar.xz
2 Creation d'un nouveau repository public called frogr https://github.com/lephotographelibre/frogr avec un Readme
3  sutr le PC

cd ~/000_JMDEV/projects
 git clone https://github.com/lephotographelibre/frogr.git (Vide à part Readme)
cd frogr


4  Extraire les sources du projet du fichier frogr-0.11.tar.xz dans le répertoire frogs
5
$git status
$ git add
$ git status
$ git commit -m "Import from FrogR 0.11"  => Commit local
$git remote -v   ==> Verification que le projet est bien connecté au git remote 
origin	https://github.com/lephotographelibre/frogr.git (fetch)
origin	https://github.com/lephotographelibre/frogr.git (push)

$  git push            ==> Push vers le git Remote Github

warning: push.default n'est pas défini ; sa valeur implicite change dans Git 2.0
de 'matching' vers 'simple'. Pour supprimer ce message et maintenir
le comportement actuel après la modification de la valeur de défaut, utilisez :

  git config --global push.default matching

Pour supprimer ce message et adopter le nouveau comportement maintenant, utilisez :

  git config --global push.default simple

Quand push.default vaudra 'matching', git poussera les branches locales
sur les branches distantes qui existent déjà avec le même nom.

Dans Git 2.0 Git utilisera par défaut le comportement plus conservatif 'simple'
qui ne pousse la branche courante vers la branche distante que 'git pull' utilise
pour mettre à jour la branche courante.
 
Voir 'git help config' et chercher 'push.default' pour plus d'information.
(le mode 'simple' a été introduit dans Git 1.7.11. Utilisez le mode similaire
'current' au lieu de 'simple' si vous utilisez de temps en temps d'anciennes versions de Git)

Username for 'https://github.com': lephotographelibre@yahoo.com
Password for 'https://lephotographelibre@yahoo.com@github.com': 
Counting objects: 401, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (377/377), done.
Writing objects: 100% (400/400), 3.10 MiB | 583.00 KiB/s, done.
Total 400 (delta 174), reused 0 (delta 0)
To https://github.com/lephotographelibre/frogr.git
   c4626f8..c53cff7  master -> master
