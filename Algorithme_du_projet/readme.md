# Projet VDJ-Kernel

## Membres :
EL GHOUL Elio
KHOW Antoine

## Mise en place de l'environnement :
Il faut en premier lieu télécharger tout le répertoire `Algorithme_du_projet` et de déplacer à l'intérieur

## Exécution :
Assurez-vous en premier lieu que les répertoires `human_germline` et `VDJ-Kernel-main` se trouvent dans le même répertoire que les fichiers sources, ces répertoires contiennent les données utilisées que nous détaillerons plus bas.
Pour exécuter l'algorithme, il suffit d'ouvrir les fichiers `.ipynb` en utilisant Jupyter-notebook ou autre IDE supportant les notebook python. Attention, il faut exécuter **dans l'ordre suivant** les fichiers : 
- `_1EA_algorithm_v2v.ipynb`
- `_1EA_algorithm_v2j.ipynb`
- `_1EA_algorithm_v2d.ipynb`
- `_1EA_algorithm_v2dhmm.ipynb` 

Une fois les 4 fichiers précédent exécutés, il ne reste plus qu'à ouvrir et exécuter le fichier `Fichier_execution.ipynb`.

## Architecture du code :
Le projet a été divisé en 3 grandes parties :
- La partie d'identification des gènes V (`_1EA_algorithm_v2v.ipynb`)
- La partie d'identification des gènes D (`_1EA_algorithm_v2d.ipynb` et `_1EA_algorithm_v2d.ipynb`)
- La partie d'identification des gènes J (`_1EA_algorithm_v2j.ipynb`)

## Architecture des données :
Les données sont situées dans le même répertoire que les fichiers sources du code, on y retrouve :
- Le répertoire `VDJ-Kernel-main` qui contient les données simulées avec lesquelles nous avons testé notre algorithme
- Le répertoire `human_germline` qui contient les gènes de références pour les gènes V, D et J (Database)
- Le rapport du projet (`M1_Projet_BIM_Elio_EL_GHOUL_Antoine_KHOW.pdf`)
