# Star-Wars-Crawl
Exercice Prairie HTML - CSS - 7-exercice-star-wars

## Les étapes à suivrent

* Trouver un fond étoilé le mettre en background-image
* Trouver le logo becode et le placer avec le texte défilant dans une div pour que la transformation s'applique au logo et au texte.
* Créer du texte sur plusieurs paragraphes en lorem ipsum.
* Donner couleur jaune, police sans serif et taille plus grande au texte
* Sur la div contenant le logo et le texte appliqué une transformation pour donner un effet 3D perspective et rotateX avec une origine de transformation centrée.
* Placé ce bloc de texte hors de l'écran en lui appliquant une position absolue et un top de 100% (le texte est placé juste sous l'écran) pour pouvoir avoir le bon point de départ pour l'animation.
* Créer l'animation avec @keyframes pour faire remonter le texte vers le haut de la page (de top: 100% à top: 0% (au écran)) et ensuite le faire disparaitre vers la fin avec une opacité 0 à environ 80% de l'animation.
* Ajouter de la musique avec la balise audio et autoplay pour que le son se joue tout seul au chargement de la page (avec les controls ce n'est pas esthétique même si autoplay est déconseillé car irritant pour les utilisateurs qui ne peuvent pas choisir ou pas de lancer le son)

## Les problèmes que j'ai rencontré

* Mon animation du texte d'intro se superposait avec mon animation de défilement de texte
* Problème de positionnement jusqu'à inclure une autre div dans la div défilant pour pouvoir appliqué des propriété spécifiques différentes à la div défilant *conteneur* et la div se trouvant à l'interieur *contenue*
*

## Ce que j'ai appris

* Application pratique des animations et transformations apprises avec openclassrooms - cours css avancés suivi cet été
* L'unité de mesure en em n'est pas uniquement réservée à la taille des polices de caractères, on peut également l'utiliser pour définir une hauteur de bloc par exemple. Pour me familiariser avec cette notion, j'ai lu cet [article très intéressant sur stackoverflow](https://stackoverflow.com/questions/609517/why-em-instead-of-px)
* En utilisant un positionnement en absolute et en jouant avec l'attribut top exprimé en pourcentage, on peut placer un élément en haut de la page(0%) ou en dessous de la page (100%) (si on a un overflow:hidden, sinon apparition de scrollbarre)
* Découverte de la propriété overflow désignant le contenu de l'écran et overflow: hidden permettant de caché tout ce qui dépasse de l'écran et fait disparaitre les scrollbarres.


## Ce que j'aimerai approfondir dès que j'en ai le temps

* Pour éviter l'autoplay sur la musique je voudrais ajouter un bouton on-off pour le son mais pas audio controls car affiche une barre de controle inesthétique en plein milieu de la page.
IL faudrait semble-t-il faire appel à deux fonction javascript pour faire cela. J'ai déja trouvé ces liens pour m'aider:
https://www.w3schools.com/tags/tryit.asp?filename=tryhtml5_av_met_play_pause
https://www.w3schools.com/tags/av_met_pause.asp
https://openclassrooms.com/forum/sujet/bouton-on-off-avec-musique-de-fond
Je vais commencer l'apprentissage du javascript demain, je reviendrais ajouter cette fonctionnalité dès que je comprendrais mieux ce langage.


