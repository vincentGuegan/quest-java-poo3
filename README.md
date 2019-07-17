# Challenge

#### I Believe I Can Fly !


1.  Parcours le dépôt et observe son contenu :
    -   `Bird`, classe abstraite
    -   `Eagle`, classe héritée de  `Bird`
    -   `Swim`, une interface
    -   `Penguin`, classe héritée de  `Bird`  qui implémente  `Swim`
    -   `Nature`, que tu compileras et exécuteras pour tester que tout fonctionne
2.  Crée une interface  `Fly`
3.  Ajoute les méthodes suivantes à l'interface  `Fly`  :
    -   `takeOff`  sans argument, qui ne retourne rien
    -   `ascend`  qui prend un entier  `meters`, qui retourne un entier
    -   `descend`  qui prend un entier  `meters`, qui retourne un entier
    -   `land`  sans argument, qui ne retourne rien
    -   `glide`, sans argument, qui ne retourne rien et qui possède un comportement par défaut : afficher le texte "It glides into the air."
4.  Faire implémenter l'interface  `Fly`  par la classe  `Eagle`
    -   Tu pourras décider des comportements des méthodes, mais il est obligatoire que chaque méthode affiche du texte dans la console.
    -   Tu peux t'inspirer de l'implémentation de  `Swim`  par  `Penguin`
5.  Décommente l'appel des méthodes de  `Eagle`  dans  `Nature`
6.  Compile et teste  `Nature`. Quand tout fonctionne, crée un dépôt  _git_  et envoie le tout sur  _GitHub_
7.  Partage le lien du dépôt  _GitHub_  en solution

Exemple de résultat lors de l'exécution de  `Nature`  :

```java
$ Eye Cherry takes off in the sky.
$ Eye Cherry flies upward, altitude : 120
$ Eye Cherry flies upward, altitude : 150
$ It glides into the air.
$ Eye Cherry flies downward, altitude : 10
$ Eye Cherry is too high, it can't lands.
$ Eye Cherry flies downward, altitude : 1
$ Eye Cherry lands on the ground.

```

#### Critères de validation

-   Le dépôt  _GitHub_  contient bien le fichier  `Fly.java`
-   Les classes et interfaces respectent les conventions de la POO : attributs privés, utilisation du mot-clef  _this_,  _getters_  et  _setters_  nommés correctement
-   La classe  `Eagle`  implémente l'interface  `Fly`
-   La classe  `Nature`  contient l'appel des méthodes d'une instance de  `Eagle`
-   La classe  `Nature`  se compile sans erreur et affiche dans le terminal un résultat proche de celui présenté précédemment