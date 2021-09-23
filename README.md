# OHMYFOOD 
------
Troisième projet de mon parcours de Développeur Web avec Openclassrooms.
Objectif du projet : Dynamiser une page web avec des animations CSS, ici le site d'une jeune startup qui répertorie des menus de restaurants gastronomiques nommé Ohmyfood.
------
## Cahier des charges/Livrables
### Les pages à intégrer : 
- Page d'accueil.
- Pages comportant les menus des restaurants (x4).
### Effets graphiques et animations :
#### Boutons
- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. 
L’ombre portée devra également être plus visible.  
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un 
bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se 
remplir progressivement. Pour cette première version, l’effet peut être apparaître au 
survol sur desktop au lieu du clic. 
#### Page d'accueil
- Quand l’application aura plus de menus, un "loading spinner" sera nécessaire. Sur 
cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 
3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et 
utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, 
toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte 
graphique du site.
#### Pages de menus 
- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger 
décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe 
"Entrée", "Plat" et "Dessert". Un exemple de l’effet attendu est fourni. 
● Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. 
Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de 
la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol 
sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec 
des points de suspension. Un exemple de l’effet attendu est fourni. 
------
## Contraintes techniques
### Identité graphique :
**Polices :** "Shrikhand" pour le logo et les titres et "Roboto" pour les textes.
**Couleurs :** "Primaire":#9356DC / "Secondaire":#FF79DA / "Tertiaire":#99E2D0.
### Enjeux :
- Phase 1 : Développer un site proposant le menu de 4 grands restaurants parisiens. 
- Phase 2 : Permettre la réservation en ligne et la composition de menus. 
### Compatibilité : 
- Le site sera développé en utilisant l’approche mobile-first. Pour cette raison, seules des maquettes mobiles seront réalisées. 
- Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires, leur mise en page est libre. 
- L’ensemble du site devra être responsive sur mobile, tablette et desktop.
- Les pages devront passer la validation W3C en HTML et CSS sans erreur.
- Le site doit être parfaitement compatible avec les dernières versions desktop de 
Chrome et Firefox. 
------
## Informations complémentaires
- Le développement devra se faire en CSS, sans JavaScript.
- Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS serait un plus. 
- Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.
------
## Outils et langages utilisés 
- HTML5/CSS3, SASS (préprocesseur CSS).
- Git Graph.
- Live Server de VSCode.
- Terminal Powershell de VSCode.