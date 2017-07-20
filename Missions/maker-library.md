Encore quelques questions lors de la création d'une mission.

- *quid de l'organisation des fichiers?*
Dossier spécifique dans dossier mission
- *où stocker les fichiers?*
Dans son dossier
- *une nouvelle branche?*
Oui, pour passer par un pull request.
- *un nouveau repo?*
Seulement lorsqu'on passe à une quête.

# MakerLib - test production
ref to file.md or #issue : [openfab/issues/42](https://github.com/openfab-lab/openfab/issues/42)
## Contexte
Suite à la visite de Vincent Demuliere qui cherche à ouvrir une librairie en mode maker et opensource via le concept de [maker librairies](http://design.britishcouncil.org/projects/makerlibraries/)
ça ma donné bien envie d'essayer.
## objectif
Ils nous manquent tjs pas mal de mobilier pratique pour ranger, afficher, présenter clairement où sont les tools, les consommables, les projets en cours, ce qu'on peut acheter et à quel prix.
J'aimerai tester ce système pour le Buro274.
Les avantages sont multiple: 
- c'est modulable, 
- c'est pas cher (uniquement vis, colle et bois en section carrée 3cm)
- c'est réalisable sans machine numérique, 
- s'assemble n'importe où,
- c'est léger.
## Proposition
- [x] Je vais modéliser une box selon le pdf fournis
- [x] tester sur un petit modèle. basé sur une petite cagette plastique bleu (400x295x200mm)
- [x] acheter du bois chez Brico (7.78€)
- [x] Découpe en longueur ad-hoc
- [x] ~~Tenon à la scie radiale~~ nope,bad idea
- [x] Tenon à la défonceuse (mèche 8mm)
- [x] assemblage à la colle + vis 
### Ressources
#### Bois: 
- [Gedebois](http://www.gedebois.be/catalogue-2017/bois/sapin-rabote.html): section rabotée 27x27mm = 1.95€/m, 35x35mm = 2.60€/m
- Brico: section rabotée 34x34mm = 3,89€/1.8m
#### software
Fusion360
## Résultats
![screenshot 28](https://user-images.githubusercontent.com/12049360/27784836-e394a3a6-5fdb-11e7-9873-bc405016bf94.jpg)

[Le modèle](http://a360.co/2sDIXWT) est paramétrique et peut être facilement modifié pour
  - hauteur x longueur x largueur 
  - section bois  

Ce qui donne plus facilement une idée précise des longueurs bois nécessaire. Reste à faire un plan de découpe en fonction des longueurs disponibles au shop.  
**Durée: 2h**

![img_20170702_145003_800_600](https://user-images.githubusercontent.com/12049360/27784782-a7e08668-5fdb-11e7-928a-002a1971500b.jpg)

[Production et assemblage proto01](/Gamification/Missions/maker-library-proto01.md)  
**Durée: 3h**  
Ouais, j'ai un peu galéré, c'est le premier... 
### Rewards
Je vais passer ce projet en mission et si ça fonctionne bien, que j'arrive à automatiser et faciliter la production avec des gabarits malin:
- J'aimerai valider mes badges (nécessite encore un processus et des logos. Voir plus en détail openbadge)
  - [ ] Fusion360 - "habile"
  - [ ] 3Dprint - "habile"
  - [ ] Défonceuse - "bon"
  - [ ] Astuce - "habile"
  - [ ] Foreuse - "habile"
  - [ ] Visseuse - "habile"
- Je serai super content de pouvoir résoudre un problème de plus dans l'amélioration du buro274. **= 2dèbières**
- Et j'aimerai ajouter cette solution au catalogue avec la capacité à sa réalisation.
