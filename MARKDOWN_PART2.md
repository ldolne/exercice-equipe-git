Liens:
* [Lien vers partie 1](https://github.com/ldolne/exercice-equipe-git/blob/master/MARKDOWN_PART1.md)
* [Lien vers le README](https://github.com/ldolne/exercice-equipe-git/blob/master/README.md)


# Les paragraphes
(rajouter deux espaces à la fin du paragraphe)

    Ceci est un paragraphe
    Ceci est un autre paragraphe

Résultat:  
Ceci est un paragraphe  
Ceci est un autre paragraphe  

# Les titres

    # Titre de niveau 1
    ## Titre de niveau 2
    ### Titre de niveau 3
    #### Titre de niveau 4
    ##### Titre de niveau 5
    ###### Titre de niveau 6

Résultat:
# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4
##### Titre de niveau 5
###### Titre de niveau 6

# Les textes gras, italiques et barrés

    *Ceci est un texte italique*,  **Ceci est un texte gras** et ~~Ceci est un texte barré~~
    **Il est possible de les *combiner* comme ceci** ou *encore comme **ceci***
Résultat:  
*Ceci est un texte italique*,  **Ceci est un texte gras** et ~~Ceci est un texte barré~~
**Il est possible de les *combiner* comme ceci** ou *encore comme **ceci***

    _Ceci est un texte italique_ et __Ceci est un texte gras__ et ~~Ceci est un texte barré~~
    __Il est possible de les _combiner_ comme ceci__ ou _encore comme __ceci___
Résultat:  
_Ceci est un texte italique_ et __Ceci est un texte gras__ et ~~Ceci est un texte barré~~
__Il est possible de les _combiner_ comme ceci__ ou _encore comme __ceci___

# Les liens

    [Ceci est un lien](https://wprock.fr/blog/)
    [Ceci est un lien avec un titre](https://wprock.fr/blog/ "Le titre du lien")
    Ceci est un lien automatique : <https://wprock.fr/blog/>
    Ceci est un lien email : <exemple@wprock.fr>

Résultat:  
[Ceci est un lien](https://wprock.fr/blog/)  
[Ceci est un lien avec un titre](https://wprock.fr/blog/ "Le titre du lien")  
Ceci est un lien automatique : <https://wprock.fr/blog/>  
Ceci est un lien email : <exemple@wprock.fr>  

# Les listes simples et ordonnées

    Liste simple : 
    * Élément 1
    * Élément 3
      * Sous-élément 1
      * Sous élément 2
    * Élément 2
    Liste ordonnée : 
    1. Élément 1
    2. Élément 2
      1. Sous-élément 1
      2. Sous élément 2
    3. Élément 3
    Listes simples et ordonnées imbriquées : 
    1. Élément 1
      * Sous-élément 1
      * Sous élément 2
    2. Élément 2
    3. Élément 3

Résultat:  
Liste simple : 
* Élément 1
* Élément 3
  * Sous-élément 1
  * Sous élément 2
* Élément 2
Liste ordonnée : 
1. Élément 1
2. Élément 2
  1. Sous-élément 1
  2. Sous élément 2
3. Élément 3
Listes simples et ordonnées imbriquées : 
1. Élément 1
  * Sous-élément 1
  * Sous élément 2
2. Élément 2
3. Élément 3

# Checklist / Liste de cases à cocher 

    - [x] Élément 1, coché
    - [ ] Élément 2, non-coché
      - [x] Sous-élément 2.1, coché
      - [ ] Sous-élément 2.2, non-coché
    - [ ] Élément 3, non-coché

Résultat:  
- [x] Élément 1, coché
- [ ] Élément 2, non-coché
  - [x] Sous-élément 2.1, coché
  - [ ] Sous-élément 2.2, non-coché
- [ ] Élément 3, non-coché

# Liste de définitions

    Terme 1
    : Définition 1.1
    Terme 2
    : Définition 2.1
    : Définition 2.2

Résultat:  
Terme 1
: Définition 1.1
Terme 2
: Définition 2.1
: Définition 2.2
(mais pourquoi ça fonctionne pas???)

# Les caractères speciaux

Lorsqu' on veux ecrire des caratères specaux dans le text il faut le faire précéder d'un backslash.

	\\   : Anti-slash
	\`   : Apostrophe curve
	\*   : Asterisk
	\_   : Low dash / Underscore
	\{\} : Braces
	\[\] : Hooks
	\(\) : Parentheses
	\#   : Sharp
	\+   : Sign more
	\-   : Less sign / hyphen
	\!   : Exclamation dot
	\.   : Dot
	
#Introduire une image

	![Texte alternatif](https://wprock.fr/wp-content/uploads/2018/11/wprock-wallpaper-wapuu-wordpress-paris-520x254.jpg "Titre, facultatif")
	
	
#Markdown : Les citations

	> Ceci est une citation
	> - Source
	
	
#Markdown : Séparateurs / Lignes horizontal

	***
	
	
#Code MD et HTML – Sans alignement

	Titre colonne 1 | Titre colonne 1 | Titre colonne 1 
	 --- | --- | --- 
	Celule 1.1 | Celule 1.2 | Celule 1.3 
	Celule 2.1 | Celule 2.2 | Celule 2.3 
	
	
#Code MD et HTML – Avec alignement
	Titre colonne 1 (droite) | Titre colonne 1 (centré) | Titre colonne 1 (gauche)
	 ---: | :---: | :--- 
	Celule 1.1 | Celule 1.2 | Celule 1.3 
	Celule 2.1 | Celule 2.2 | Celule 2.3 
	
	
#Markdown : Codes et textes préformatés
	Mon code : `alert("Hello wpRock");`
	
	
#Code MD et HTML – Pleine largeur
	```
	alert("Hello wpRock");
	```


![Link](https://media.giphy.com/media/YWUpVw86AtIbe/giphy.gif)
