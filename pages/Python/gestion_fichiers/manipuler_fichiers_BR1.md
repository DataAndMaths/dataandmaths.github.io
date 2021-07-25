---
layout: page
title: Python
subtitle: Manipuler des fichiers
---

* **chdir()** : change directory
* **open()** : 
  * ouvrir un fichier : en fait il crée un 'objet' qui permet de manipuler le fichier 
  * arguments :
    * argument 1 : nom du fichier
       * si le fichier n'existe pas, il sera crée
    * argument 2 : mode d'ouverture
       * **'a'**= append (pour ajouter les données à la fin du fichier)
       * **'w'** = write (aussi pour écrire ... mais attention : il crée automatiquement un nouveau fichier, ce qui écraserait un fichier existant du même nom)
       * **'r'** = read (pour lire les données du fichier)
      
* **close()** : fermer un fichier qui a été ouvert
* **write()** : écrire de nouvelles données dans le fichier 
* **read()** : lire toutes les données d'un fichier (qu'on enregistre dans une variable, pour les afficher avec un print)
   * argument optionnel : nombre de caractères à lire
   * NB: si on fait deux read à la suite, par exemple read(3) puis read(5), le deuxième se fera à partir de la position atteinte précédemment.
 


* source : [Swinnen]