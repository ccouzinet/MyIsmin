# MyISMIN

Le site a été réalisé avec le moteur [*jekyll*](http://jekyllrb.com/). 

### Éditer le site
Vous pouvez rédiger les pages en HTML ou en markdown. Des variables ont été ajoutées pour ajouter l'image d'entête (*banner*), un logo avant le titre du club/asso (*logo*) et un texte en dessous du titre "MyIsmin" (*subheader*). Le nom de la page dans le menu est défini par la variable *name*, et le titre de la page par la variable *title*. Pour les pages d'asso/club, le `layout: page` est obligatoire.

Les pages concernant les assos sont dans le dossier `assos/_posts`, celles concernant les clubs sont dans `clubs/_posts`. Les nouvelles pages (assos/clubs) doivent s'appeler AAAA-MM-JJ-Nom-De-L-Asso.html. (Cette architecture de dossiers et le nommage des pages sont imposés par jekyll).
Lorsque vous ajoutez une page dans un de ces dossier, l'entrée correspondante est automatiquement ajoutée au menu.

### Génération du site avec jekyll
La génération est plutôt aisée, il suffit de *build* le site avec la commande `jekyll build [-d /output/directory]`.

Pour développer tranquillement sans avoir à re-build à chaque changement, vous pouvez utiliser `jekyll serve` qui va créer un serveur et regénérer le site à chaque changement de fichier.

## Contact

Le site a été réalisé principalement par :
* [Thomas TROUCHKINE](https://github.com/Kerzas)  ( thomas.trouchkine@gmail.com )
* [Mathieu ROUSSE](https://github.com/m-rousse)  ( mathieu@rousse.me )

N'hésitez pas à nous contacter pour toutes remarques ou questions !
