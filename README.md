TP  atelier Big DATA

Partie 1 : installation des composant

Docker

 Linux : https://docs.docker.com/desktop/install/linux-install/
Windows :  https://docs.docker.com/desktop/install/windows-install/
mac : https://docs.docker.com/desktop/install/mac-install/



Conduktor

all os : https://www.conduktor.io/get-started/#desktop



Spark


spark: https://cedric.cnam.fr/vertigo/Cours/RCP216/installationSpark.html#installationspark

attention pre-requis : JDK ou openJDK 1,8 (8)

Faites les installations mais les versions de spark ayant évoluer faites en sorte de manipuler le spark que vous avez télécharger.


Python avec miniconda :

Personnellement j’utilise Python avec Miniconda mais faites comme vous le sentez

all os :  https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html


suite jetbrain :

avec l’ecole vous avez le droits a Pycharm et IntelliJ de la suite Jetbrain :
Faites un compte etudiant avec le mail de l’école qui vous offrira un compte gratuit :

https://www.jetbrains.com/







Partie 2 : Mise en place

docker :

Lancer la commande :  docker compose up -d (linux)
ou docker-compose up -d (windows)

dans le repertoire ou sont stocké les fichier docker-compose,yml


Vous verrez ce type d’instance ce Metttre en route sur le docker engine

(petit tips :  installer git bash sur windows pour pouvoir manipuler comme du linux )


Code :


Telecharger le code compresser sur discord

Vous avez le choix de programmer en SCALA
ou en PYTHON au choix.





Partie 3 : consigne

Partie 1 :

si python finir le produceur pour envoyer la donnée dans kafka
Si scala , consumer déjà tout prêt


Partie 2 :

Recuperer les donnée via spark streaming ou kafka-stream
stocker cette donner en dataframe

puis faire des aggregats dessus :
#       convertir USD en EUR
#       ajouter le TimeZone
#       remplacer la date en string en une valeur date
#       supprimer les transaction en erreur
#       supprimer les valeur en None ( Adresse )

Partie 3 :

ecrire le nouveaux DATAFRAME au format parquet sur Minio


Partie 4 option

Lire le fichier nouvellement cree sur Minio avec spark
![image](https://github.com/Myriuss/tp_datalake/assets/62858015/3b4bd387-b2ed-48ac-accb-cd9c70e6f5a7)
