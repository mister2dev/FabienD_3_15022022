﻿# Ohmyfood

## Projet 3 du parcours Développeur Web d'Openclassrooms.

Objectif : Dynamisez une page web avec des animations CSS

Ohmyfood! est une entreprise de commande de repas en ligne permetant aux
utilisateurs de composer leur propre menu et de réduire leur temps d’attente dans les
restaurants car leur menu est préparé à l’avance.



<img src="https://user.oc-static.com/upload/2020/08/24/15982605908418_Maquettes%20Ohmyfood.jpg" alt="maquette du site" />



## Caractéristiques techniques

**Polices :**
- Logo & titres: Shrikhand
- Texte: Roboto

**Couleurs :**
- Primaire: #9356DC
- Secondaire: #FF79DA
- Tertiaire: #99E2D0

**Technologies :**

- CSS sans JavaScript.

- Aucun framework autorisé mais SASS serait un plus.

- Aucun code CSS via un attribut style dans une balise HTML.

- Tout le code doit être versionné sur GitHub et le site devra être accessible sur
Github Pages une fois terminé.

**Compatibilité :**

Le site sera développé en utilisant l’approche mobile-first. Pour cette raison, seules des maquettes mobiles seront réalisées.
Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires,
leur mise en page est libre.

- L’ensemble du site devra être responsive sur mobile, tablette et desktop.

- Les pages devront passer la validation W3C en HTML et CSS sans erreur.

- Le site doit être parfaitement compatible avec les dernières versions desktop de
Chrome et Firefox.

## Livrables

### Contenu des pages

**Page d’accueil (x1)**

- Affichage de la localisation des restaurants.
- Une courte présentation de l’entreprise.
- Une section contenant les 4 menus sous forme cartes. Au clic sur la carte,
l’utilisateur est redirigé vers la page du menu.

**Pages de menu (x4)**

- Quatre pages contenant chacune le menu d’un restaurant.

### Effets graphiques et animations

**Boutons**

- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir.
L’ombre portée devra également être plus visible.

- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un
bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se
remplir progressivement. Pour cette première version, l’effet peut être apparaître au
survol sur desktop au lieu du clic.


**Page d’accueil**

- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur
cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à
3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,
toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte
graphique du site.


**Pages de menu**

- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe
“Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.

- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de
la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol
sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec
des points de suspension. Un exemple de l’effet attendu est fourni.