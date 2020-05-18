# Star Wars Rebels Alliance Search System
Bienvenue dans l'Alliance Rebelle jeune Padawan!<br/>
Nous avons besoin de personnes motivées pour défaire l'Empire.

Les espions du seigneur Vader sont partout! <br/>
Il nous faut donc un moyen de contrecarrer leurs plans.

C'est pourquoi nous avons décidé de vous confier une mission de la plus haute importance!

Il s'agira, pour le bien de la rébellion de créer une interface nous permettant de rechercher dans la banque de données de l'empire.  <br/>
L'un de nos espion a donné sa vie afin que nous puissions accéder à ces informations.
 
La base de données de l'Empire est accessible [à cette URL](https://swapi.dev/).

## Objectifs de mission

### Etape 1
Création d'un back-end en Node permettant de récupérer les données de SWAPI <br />
Il vous faudra implémenter un endpoint pour faire une recherche globale, incluant toutes les ressources. <br />
Elle devra prenndre en compte ce que la deuxième étape va demander. <br />
Un autre endpoint pourrait être requis pour les films. <br />
L'utilisation d'[HAPI](https://hapi.dev/) est un plus.

### Etape 2
Création d'un front-end en ReactJS permettant de rechercher facilement sur le back-end créé au préalable. <br/>
Vous devrez implémenter des filtres, à savoir:
 - Un choix des films dans lesquels la ressource est impliquée.

Chaque ressource doit être affichée avec son image, et au clic ouvrir une fiche un peu plus détaillée.

Dans le cadre de notre collaboration avec nos alliés Wookies, il serait préférable de donner
la possibilité de traduire les résultats dans la langue de nos amis poilus.

Cependant vous aurez quelques contraintes:
 - Utilisation d'un router pour la navigation entre les différentes ressources.
 - Utilisation de redux, parce-que pourquoi pas.

Attention, l'utilisation de [swapi-node](https://www.npmjs.com/package/swapi-node) est prohibée, car l'application est surveillée par l'empire. <br/>
Afin que le service de renseignement de l'alliance puisse vérifier l'intégrité de votre code, il sera nécessaire de le mettre sur un repo git.

## Conclusion
Toute l'alliance Rebelle compte sur la réussite de cette mission.

![May the force be with you](https://media.giphy.com/media/JDnaQ8qn0Myuk/200.gif)
