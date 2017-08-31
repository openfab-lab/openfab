# Préparation du fichier avant découpe et/ou gravure laser.

## La raison d'être de ce document

La préparation est une étape cruciale du processus, cela peut vous éviter une belle perte de temps à faire des aller-retours entre l'interface de la machine et le logiciel de dessin vectoriel. Ce document vient donc vous accompagner dans ce processus. Sentez vous libre de l'affiner, le compléter voire même de documenter la suite du processus pour couvrir l'intégralité d'une découpe/gravure laser, ...

## Préparation

### Logiciel

- (Recommandé) Inkscape, un équivalent d'Illustrator mais open source, gratuit. D'autant que c'est celui-ci que nous avons sur les ordinateurs du FabLab, si vous avez besoin d'effectuer une correction. Mais rien ne vous empêche de tout faire via Illustrator sur votre machine. Téléchargeable [ici](https://inkscape.org/fr/). Attention, il y a un problème de conversion entre Inkscape et Illustrator, cela va modifier la taille de votre dessin.  

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/Inkscape_Logo.svg/1024px-Inkscape_Logo.svg.png" width="60">

### Votre fichier

- Format document : .svg

- Préparez les contours : 
La découpeuse ne prend en compte que les "chemins" et donc les contours de vos formes. De plus, le faisceau fait 0,4mm de diamètre donc pour bien rendre compte du résultat, nous vous conseillons de déjà paramétrer les contours correctement (avec Objet > Remplissage et contour...). D'autant plus si votre visuel est proche des bords de la zone de travail (s'il en sort, la machine n'arrivera pas à le lire).

  Cas particulier : Mettre du texte.  
Si vous voulez écrire un mot sur votre visuel, les objets texte ne sont pas lisibles par la machine. Pour se faire, il faut sélectionner votre texte et cliquez sur Chemin > Contour en chemin.

  **Une bonne manière de visualiser ce que verra la machine est de cliquer sur Affichage > Mode d'affichage > Contour.**

- 1 couleur = 1 règlage :   
L'application de la machine vous permet d'associer un réglage (vitesse et intensité du laser) à une couleur. Ce qui est très pratique pour pouvoir réaliser une pièce complexe alliant découpe (laser lent et intense) et gravure (laser rapide et peu intense). D'ailleurs, il est fortement recommandé de commencer par la gravure car la découpe va faire bouger, tomber des pièces. Pour la même raison, il faut commencer par découper l'intérieur d'une pièce avant de faire son contour. Il est donc important d'utiliser encore une fois l'outil "Remplissage et contour..." présenté précédemment pour dissocier, avec des couleurs différentes : gravure, découpe, intérieur, contour, ...
 
- Enregistrez son fichier :  
Cela semble être une étape simple, ça l'est mais il y a un peu piège : évitez les accents et caractères spéciaux sinon la machine n'arrivera pas à le lire et vous chercherez l'erreur partout sauf dans le nom de votre fichier.  

### Exemple

Mégalo comme je suis, je souhaite avoir mon prénom écrit dans un morceau de bois pour ma chambre ! Je souhaite que "Paul" soit découpé dans un rectangle gravé, lui-même dans un rectangle découpé, servant de contour.

Mon fichier va donc ressembler à ça avec 3 couleurs distinctes :

<img width="406" alt="inkscape tuto" src="https://user-images.githubusercontent.com/7775797/29928349-0a738878-8e69-11e7-85aa-5a4bbd788667.png">

Quand je passerai aux réglages de la machine, je lui demanderai de faire sa première "Pass" sur le bleu (gravure) puis le rouge (intérieur) et finalement le noir (contour de la pièce). Une inversion entre bleu et rouge ne changera pas grand chose mais surtout finissez par le noir ! Le choix de ces couleurs est complètement arbitraire, libre à vous de mettre du violet, du marron, ... C'est une réalité, peut-être abstraite avant les premières expériences, mais qu'il est bon d'intégrer dans la préparation de son fichier.

## Résumé des astuces

- Attention au nom du fichier, il vaut mieux éviter les caractères spéciaux, accents, ...
- Attention, si vous faites des aller-retours entre Inkscape et Illustrator, il y a un soucis de conversion des unités, votre fichier sera réduit sur Inkscape, il faudra donc le redimensionner comme il convient.
- Attention, votre travail ne doit pas sortir de la zone de travail sur votre logiciel de dessins. N'oubliez pas que les contours font 0,4 mm. La machine sera dans l'incapacité de le lire.
- Préférez Firefox à Chrome ou tout autre navigateur web, il peut arriver que le fichier ne passe que sur ce premier.
