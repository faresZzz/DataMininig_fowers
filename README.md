# Data Mining Project


Ce projet est un projet de classe et a pour but de découvrir et experimenter le data mining ainsi que d'avoir une premier approche d'un system de recommendation.
Dans notre projet nous avons utiliser la base de donnée  ***104 Flowers: Garden of Eden*** tirée du site ***Kaggle***. C’est un ensemble de différentes espèces de fleurs tirée de plusieurs data bases publiques. Il comprend plusieurs dossiers. Les images sont disponibles en plusieurs tailles. Toutes les images sont au format jpeg, et libres de droit. Nous n'utilisons qu'une partie ce celle-ci soit 5000 images, mais nous pouvons facilement étendre ce chiffre




### Pré-requis

Afin de pouvoir executer notre programme correctement, vous aurez besoin des bibliothèques Python suivante:

- pandas
- numpy
- sklearn
- PIL
- matplotlib
- tkinter

Ainsi que de la bibliothèque d'image provenant de ***Kaggle***

### Installation
Pour commencer vous devers mettre tout les images dans un dossier nommé: **flowers**
de sorte a obtenir l'arborescence suivante
```
    /flowers
        /jpeg-192x192
        ...
        /jpeg-512x512
        
```      

## Démarrage

Role de chaque partie
---
1. La partie ***1*** sert a charger la banque de donnée de couleurs normalisé

2. La partie ***2*** sert a charger toutes les images ainsi que réaliser l'extraction des couleurs (Peut être sauter si valeurs par default)

3. La partie ***3*** est le coeur du programmes avec la creation des 3 classes principales du système:
    - La classe User qui représente un utilisateur.
    - La classe RecommendationSystem qui représente le system global contenant les utilisateurs.
    - La partie Gui permettant pour le moment uniquement d'afficher les images

3. La partie ***4*** vous donnes quelques fonctions de bases du système que vous pouvez executer afin de voir sont fonctionnement

4. La partie ***5*** est une simulation de fonctionnement du système au complet 

5. Finalement la partie ***6*** est une partie permettant de visualiser les données que nous pouvons obtenir a l'aide de notre system
---

Indications sur la modifications des paramètres.
---
La partie ***2*** est modulable:
- Vous pouvez choisir le nombres d'images que vous souhaité dans votre dataset en jouant sur le paramètre ``if i < 10:``

- Vous pouvez contrôler le nombre de Kmeans que vous souhaité en jouant sur le paramètre ``nb_cluster``

- Un premier dataset à déjà été précharger dans le fichier ``data.json`` si vous souhaiter concerner les paramètres par default nous vous conseillons de passer la partie 2, et executer la 1ere case de la partie 3 afin de charger le dataset
car la réalisation de Kmeans pour l'extraction de couleurs est relativement longue.

- Un premiers set de client à été préchargé dans les fichier ``user.json linkTable.json`` vous pouvez les supprimer pour repartir avec un system de recommendation vierge

---
## Fabriqué avec

Programme réalisé en utilisant [Anaconda](https://www.anaconda.com/products/distribution) sous Python 3.9.7


## Versions

**Dernière version stable :** 1.0
**Dernière version :** 1.0

## Auteurs

* **Romain Galmier** _alias_ [@romaingalmier](https://github.com/romaingalmier)
* **Farès Zaghouane** _alias_ [@faresZzz](https://github.com/faresZzz)


## License

Ce projet est sous licence ``CCO`` 