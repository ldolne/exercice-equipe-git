# Liens
[Partie 2](https://github.com/ldolne/exercice-equipe-git/blob/master/MARKDOWN_PART2.md)
[README](https://github.com/ldolne/exercice-equipe-git/blob/master/README.md)


# Markdown : le guide du langage de balisage léger
Quand nous lisons des textes, que ce soit sur Internet, dans un magazine ou dans n’importe quel livre, nous nous attendons à une certaine mise en page. On utilise par exemple le gras pour mettre en avant des mots importants, on distingue au premier regard le titre d’un document et on utilise des présentations en forme de listes pour structurer certaines parties du document. Un tel formatage nous paraît évident, et derrière notre clavier d’ordinateur, lorsque nous rédigeons nos textes, tout cela ne nous pose aucun problème : nous changeons la taille des caractères, nous insérons des tirets et mettons certains mots et expressions en gras. N’importe quel traitement de texte offre à ses utilisateurs de nombreuses possibilités pour la mise en page des textes qu’ils éditent.

Pourtant tout n’est pas si simple. De votre côté, vous vous contentez de sélectionner le texte à formater, et votre logiciel lui donne les attributs que vous lui demandez. Avec les logiciels Word, vous ne voyez pas le véritable texte source, accompagné de ses balises. Et c’est tant mieux, à vrai dire : un tel texte est presque illisible pour un être humain.

N’importe quel éditeur de texte permet d’écrire du HTML ou du LaTeX, mais le résultat est difficilement déchiffrable pour le commun des mortels. Et c’est exactement ce que le langage de balisage Markdown souhaite changer. Il veut tirer profit du meilleur des deux univers, et être compris à la fois des machines et des hommes. Pour mettre en forme le texte, Markdown utilise des éléments intuitifs. Dans ce cas, même le texte accompagné de ses balises sera assez facile à comprendre pour les hommes.

## Sommaire
1 A quoi sert Markdown ?
2 Tutoriel Markdown : la bonne syntaxe pour vos documents

## A quoi sert Markdown ?
Tout comme HTML ou LaTeX, Markdown est un langage de balisage. Contrairement aux deux premiers langages, Markdown se veut être facile à lire par les personnes. Les balises ne doivent pas être abstraites, mais proches de leur véritable signification. Le plus simple est d’illustrer notre propos par un exemple : pour mettre en gras un mot avec HTML, on utilise soit le '< b >'- soit la balise < strong >.

Si vous écrivez un docuement dans LaTeX, utilisez (en mode texte continu) l’élément \textbf.

Ces deux balises se lisent certes assez facilement, mais sont plus difficiles à écrire, particulièrement dans le cadre de la rédaction de longs textes. Markdown simplifie ce processus en mettant tout simplement les éléments gras entre des étoiles.

Cette variante est d’une part plus lisible, car l’étoile indique facilement la mise en gras, et vous aurez par ailleurs plus vite fait de taper quatre étoiles que des balises compliquées. Avant la conversion (c’est à dire en Texte brut), un lecteur comprendra ce qu’a voulu dire le rédacteur, même s’il ne maîtrise pas la syntaxe Markdown.

Markdown présente donc avant tout un intérêt pour tous ceux qui n’ont pas de compétence particulière en informatique, ni en Webdesign, mais qui sont pourtant amenés à rédiger régulièrement des textes pour Internet. C’est le cas notamment des blogueurs qui utilisent un CMS (Content Management System). Il arrive même à des spécialistes et à des technophiles de recourir au Markdown pour rédiger des textes simples. Certains programmeurs utilisent le langage Markdown pour rédiger par exemple des documents d’accompagnement (ex. les fichiers Readme) sans même les convertir au préalable. En termes de lisibilité, le résultat sera sensiblement le même, que l’utilisateur ouvre le texte dans un lecteur Markdown ou qu’il le lise à l’état brut.

Pour les CMS les plus courants comme WordPress et Joomla, il existe des plugins permettant à ces logiciels de comprendre le Markdown. Un bon nombre de wikis, de forums (Reddit par exemple), ainsi que le générateur de site Jekyll sont capables d’interpréter ce langage de balisage simplifié.

 ### Remarque
Les langages de balisage ne sont pas des langages de programmation. Ils ont uniquement pour fonction de structurer la mise en page de votre texte. Les langages de programmation renferment quant à eux toutes sortes de boucles et de variables, et représentent le pilier même de la programmation des logiciels.

Markdown ne cherche pas à se substituer à HTML. Les fonctions qu’il propose sont assez réduites. Pour les concepteurs, le langage Markdown est plutôt un outil complémentaire. Il est d’ailleurs possible d’insérer des éléments HTML dans un document Markdown, ce qui élargit considérablement le spectre de ce langage, plutôt simple à la base. L’objectif du langage Markdown est avant tout de vous simplifier les tâches d’écriture (en particulier sur Internet). Une fois que les documents Markdown sont transformés par l’analyseur syntaxique (Parser en anglais), il en résulte des fichiers HTML susceptibles d’être utilisés avec les différents navigateurs.

 ### Note
Le nom « Markdown » est en fait un jeu de mots. Le terme anglais désignant les langages de balisage est « Markup Languages ». Le nom Markdown signifie clairement qu’on a affaire à un langage simplifié et léger, d’où l’appellation : Markdown.

## Tutoriel Markdown : la bonne syntaxe pour vos documents
Markdown étant conçu pour être un langage de balisage simple, la syntaxe Markdown est très intuitive. Pour pouvoir l’utiliser, vous devez cependant connaître les éléments de balisage. Nous avons réuni ci-dessous les principales fonctions.

Gras et italique
Écrire en gras et en italique est particulièrement facile avec Markdown. Il suffit d’utiliser les étoiles, appelées aussi astérisques. Pour écrire en italique, insérez tout simplement une étoile devant et derrière l’expression le mot ou concerné. Pour le gras, insérez deux étoiles avant et après. Pour le gras et l’italique, vous devrez opter pour trois étoiles. Une autre option consiste à utiliser les tirets bas.

*Texte en italique*
_Texte en italique_
**Texte en gras**
__Texte en gras__
***Texte en italique et en gras***
___Texte en italique et en gras___
Barré
Pour barrer un texte avec Markdown, précédez-le de deux tildes et refermez la chaîne avec deux autres tildes.

~~Ce texte est barré.~~ mais pas celui-là.
 Remarque
Markdown ne permet pas de souligner du texte. En HTML, on utilise la balise '<u>' pour souligner. Cette forme de typographie est cependant progressivement délaissée. Les hyperliens du net étant généralement représentés sous forme de texte souligné, on a tendance à ne pas souligner d’autres segments pour éviter toute confusion.

Les titres
Par défaut, pour rédiger un titre avec Markdown, on utilise le dièse. On le sépare du texte avec une espace. Pour créer des sous-titres de hiérarchie inférieure, et donc rédigés en plus petits, il suffit d’insérer des dièses supplémentaires. Comme pour l’édition HTML, vous pourrez créer jusque 6 niveaux de sous-titres.

#  Titre 1
## Titre 2
###  Titre 3
#### Titre 4
#####  Titre 5
###### Titre 6
 Note
Certains ajoutent des dièses derrière les titres. Cela peut améliorer la lisibilité, bien que ce soit absolument superflu sur le plan technique. Au moment de la conversion, ces dièses seront de toute manière ignorés.

Une autre option consiste à utiliser le signe égal et le tiret pour délimiter les titres. Il suffit dans ce cas de les insérer en dessous de la ligne du titre. Cette variante ne permet cependant de créer qu’un titre et un seul niveau de sous-titre. Un seul caractère par titre suffit, bien qu’on ait tendance à en aligner plusieurs les uns derrière les autres. La raison est purement esthétique. Plusieurs caractères successifs donnent l’impression d’un soulignement simple ou double.

Titre 1
=
Titre 2
-
Paragraphes
Le langage Markdown utilise des sauts de lignes pour créer des paragraphes séparés. Pour rédiger un nouveau paragraphe (balise

), il suffit d’insérer tout simplement une ligne vierge. Attention cependant : Markdown considère comme ligne vierge toute ligne vide sur le plan purement visuel. Si cette ligne comprend des espaces invisibles, comme des tabulations ou des espaces, l’analyseur syntaxique les ignorera et interprétera toute la ligne comme étant vierge. Si l’on souhaite insérer un saut de ligne correspondant à la balise
, il vous faudra insérer deux espaces à la fin d’une ligne.

Les citations
Pour transformer une zone de texte en citation, il est possible de créer un élément de type Blockquote avec Markdown. Pour ce faire, vous utiliserez le signe supérieur à (>). Vous pourrez soit précéder chaque ligne de ce signe, soit en insérer un au début du paragraphe et terminer le paragraphe à mettre en exergue par une ligne vierge. D’autres éléments de formatage sont possibles dans un blockquote.

>Ceci est une **zone en retrait**.
>La zone continue ici

>Ceci est une autre **zone de retrait**.
Cette zone continue également dans la ligne suivante.
Cependan, cette ligne n’est plus en retrait
Les listes
Si vous souhaitez établir une liste simple avec Markdown, vous avez le choix entre le signe plus, le tiret ou un astérisque. Ces trois options donnent le même rendu.

- Liste1
- Liste 2
- Liste 3
Pour créer une liste numérotée, il vous suffira d’inscrire un chiffre suivi d’un point.

1. Liste 1
2. Liste 2
3. Liste 3
 Conseil
Le chiffre employé n’a aucune importance pour Markdown. Que vous écriviez trois fois le chiffre 1, ou que vous commenciez par le chiffre 3, le langage Markdown rédigera dans tous les cas une liste correctement numérotée.

Markdown permet aussi d’éditer des listes à cocher. Ces listes sont précédées d’une case à cocher pouvant être activée par clic. Ces cases peuvent d’ailleurs être cochées par défaut au moment de la création de la liste. Pour ce faire, vous devez utiliser les crochets et le X.

[ ] A
[x] B
[ ] C
 Note
Pour des cases à cocher vides, n’oubliez pas de laisser une espace entre les deux crochets. Sinon Markdown n’identifiera pas votre texte comme étant une liste.

Code
Pour écrire un morceau de code dans un texte, Markdown l’identifie au moyen du caractère appelé le Backtick ou apostrophe inversée. Attention, à ne pas confondre avec les guillemets. Le marquage est donc constitué d’une apostrophe inversée au début et à la fin du segment correspondant au code. C’est ainsi que vous pourrez incorporer directement le code source ou une commande logicielle dans le texte.

C’est le `code`.
 Note
Attention cependant à ne pas écrire par mégarde un accent grave, par exemple : à. C’est ce qui risque d’arriver si vous insérez ce caractère devant une voyelle. Pour éviter ce problème, pensez à insérer une espace entre l’apostrophe inversée et la voyelle.

Si votre codage renferme déjà l’apostrophe inversée, vous devez précéder la zone de code de deux fois ce caractère. Dans ce cas, Markdown n’interprétera pas l’apostrophe inversée comme une balise.

``C’est tout le `code`.``
Pour identifier tout un bloc de texte comme du code source, vous pourrez utiliser soit la touche de tabulation ou quatre espaces consécutives, et ce pour chaque ligne concernée. Pour indenter davantage certaines lignes, il vous suffira d’insérer des tabulations ou des espaces.

Encore écrit ici en texte ordinaire
  Ceci est la première ligne du bloc de code
  La seconde ligne est encore plus en retrait
  C’est une autre ligne du bloc de code
C’est ici que le texte ordinaire recommence
Si vous préférez utiliser des caractères pour introduire et refermer des blocs de codage, il est possible d’utiliser trois apostrophes inversées au début et à la fin du bloc. Plusieurs éditeurs Markdown offrent par ailleurs la possibilité d’opter automatiquement pour un balisage de couleur. Pour ce faire, il vous faut préciser, juste après les trois apostrophes d'introduction, le langage dans lequel vous avez édité le code source.

```html
<html>
  <head>
  </head>
</html>
```

  
  
Images et hyperliens
Markdown permet aussi d’insérer des images et des hyperliens dans votre texte. Cette insertion se fait en combinant des parenthèses et des crochets. Pour créer un lien, vous devrez écrire les mots ou les phrases visibles dans le texte entre crochets, suivis directement de l’adresse URL entre parenthèses. Si vous souhaitez ajouter au lien un titre facultatif, visible par l’utilisateur au survol de la souris, c’est tout à fait possible : ce texte devra être ajouté à l’adresse URL entre les parenthèses, mais sera séparé d’une espace de l’URL, et inscrit entre guillemets doubles.

Ici ce qui suit [Lien](https://example.com/ "titre de lien optionnel").
Si vous insérez une adresse URL ou une adresse électronique dans votre texte ordinaire, la plupart des éditeurs Markdown créeront automatiquement un hyperlien accessible par clic. Pour forcer cette fonction, utilisez les signes inférieur et supérieur à. Si, en revanche, vous souhaitez empêcher les éditeurs d’activer cette fonction, marquez l’URL comme code, et utilisez à nouveau les apostrophes inversées.

<https://example.com>
`https://example.com`
La syntaxe permettant d’insérer des images est semblable à celle des liens. On commence cependant par insérer un point d’exclamation. Suivent ensuite les crochets entre lesquels on insère le texte alternatif de l’image, puis l’URL de l’image entre parenthèses. L’image sera dans ce cas directement affichée dans le texte.

![Ceci est un exemple d’image](https://example.com/bild.jpg)
 Conseil
Vous pouvez bien sûr créer des liens vers des pages HTML ou des images se trouvant sur votre propre serveur. Si le document concerné se trouve sur le même serveur, vous pouvez vous contenter de liens relatifs.

Vous pouvez aussi combiner des images et des hyperliens. Si vous souhaitez insérer un lien cliquable derrière l’image, vous devez combiner les deux fonctions. L’image devient dans ce cas le texte d’ancrage et s’affiche donc entre les crochets.

[![Ceci est un exemple d’image](https://example.com/bild.jpg)](https://example.com)
Les tableaux
Les barres verticales (|) permettent d’éditer des tableaux avec Markdown. Chaque cellule du tableau est séparée d’une barre verticale. Pour créer des lignes de titre qui se distinguent du reste du tableau, vous devrez souligner les cellules concernées avec les tirets du 6.

|cellule 1|cellule 2|
|--------|--------|
|    A    |    B    |
|    C    |    D    |
Il n’est pas nécessaire d’aligner les barres verticales les unes en dessous des autres. Si elles sont alignées, la lisibilité du tableau est cependant meilleure dans la version brute du document Markdown. La même chose s’applique aux barres verticales latérales. Elles n’ont aucune utilité pour la compilation du document.

Les notes de bas de page
Markdown vous permet aussi d’éditer des notes de bas de page. Ajoutez tout simplement dans votre texte un numéro d’annotation, et reprenez ce numéro en bas de votre page dans une note de bas de page. Markdown créera alors automatiquement une ligne. Le chiffre correspondant à l’annotation est automatiquement formaté en lien, ce qui vous permet d’atteindre la note de bas de page par un simple clic. Pour pouvoir bénéficier de cet automatisme, commencez par inscrire le numéro de l’annotation derrière le mot souhaité : commencez par écrire un accent circonflexe entre les crochets, suivi du numéro.

Le choix du chiffre (ou autres valeurs) n’a aucune espèce d’importance. Comme pour la création de liste, Markdown se charge de la numérotation. Ce qui est important, c’est de créer ensuite un renvoi vers la désignation que vous aurez sélectionnée. Pour ce faire, vous devez reprendre le même chiffre dans une nouvelle ligne, inséré à nouveau entre crochets avec un accent circonflexe, vous ajoutez le signe des deux points, et vous rédigez le texte de l’annotation. Ce texte pourra d’ailleurs faire l’objet d’un formatage de votre choix, et s’étendre sur plusieurs lignes.

Dans le texte ordinaire [^1] vous pouvez facilement placer des notes de bas de page [^2]
[^1]: Vous trouverez ici le texte de la note de bas de page.
 [^2]: **Note de page de page** peut aussi être *formatée*.
Et celles-ci comprennent même plusieurs lignes
Et celles-ci comprennent même plusieurs lignes

 Conseil
L’endroit où vous l’implantez dans le texte n’a pas d’importance. Markdown le placera dans tous les cas à la fin du document. Pour clore l’annotation et poursuivre la rédaction du corps de texte, ajoutez tout simplement une ligne vierge.

& et <>
Markdown étant très proche de HTML, il convient de regarder de plus près à l’usage du « et commercial » ainsi que les signes supérieur et inférieur. Ces caractères sont employés en HTML pour ouvrir et fermer des balises (<>) ou pour travailler avec des entités (&). Si l’on veut utiliser ces caractères dans leur signification d’origine, il faudra les masquer en HTML : &, < et >. Avec Markdown, il n’y a normalement aucune raison de ne pas utiliser ces caractères tels quels. Mais comme il est possible pour les utilisateurs de combiner Markdown et HTML, la situation est un peu complexe. Pour vous éviter de devoir faire face à de tels problèmes, l’analyseur syntaxique sait faire la différence entre les moments où vous souhaitez utiliser ces caractères et les situations de code HTML.

A & B
&alpha;
1 < 2
<p>
Masquer les barres obliques inversées
En plus des caractères spéciaux imposés par HTML, Markdown utilise quelques autres caractères pour le formatage. Si l’on insère ces caractères, l’analyseur syntaxique en tiendra compte au moment de la conversion. Voici les caractères concernés :

Astérisque : *
Trait d’union : -
Souligné : _
Parenthèses : ()
Crochets : []
Accolades : {}
Point : .
Point d’exclamation : !
Dièse : #
Accent grave : `
Barre oblique inversée : \
Si l’on veut utiliser ces caractères dans leur sens premier, il suffit de les précéder d’une barre oblique inversée. Important : Cette barre oblique inversée doit impérativement précéder chacun de ces caractères. Cela concerne donc autant une parenthèse ouvrante qu’une parenthèse fermante.

Ceci est un \*exemple avec des astérisques\*.
Ceci est un \*exemple avec des astérisques\*.
