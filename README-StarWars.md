# Star Wars Rebels Alliance Search System
Bienvenue dans l'Alliance Rebelle jeune Padawan!<br/>
Nous avons besoin de personnes motivées pour défaire l'Empire.

Les espions du seigneur Vader sont partout! <br/>
Il nous faut donc un moyen de contrecarrer leurs plans.

C'est pourquoi nous avons décidé de vous confier une mission de la plus haute importance!

Il s'agira, pour le bien de la rébellion, de créer une interface nous permettant de rechercher dans la banque de données de l'Empire.  <br/>
L'un de nos espions a donné sa vie afin que nous puissions accéder à ces informations.
 
La base de données de l'Empire est accessible [à cette URL](https://swapi.dev/).

## Objectifs de mission

### Etape 1

#### Obligatoire
 - Création d'un back-end en Node permettant de récupérer les données de SWAPI <br />
   - Implémentation d'un endpoint recherchant tout type de données sur la base de données.
   - L'API devra s'adapter aux besoins de la deuxième étape.


#### Optionnel
 - L'utilisation d'[HAPI](https://hapi.dev/) car les développeur de la rébellion l'apprécie.


### Etape 2
#### Obligatoire
 - Création d'un front-end en ReactJS permettant de rechercher facilement sur le back-end créé au préalable. <br/>
   - Création d'un champ de recherche
   - Création d'un affichage par liste des résultats avec le nom et l'image
   - Création d'une fiche détaillant le résultat où sera présentée les informations de base

#### Optionnel
 - Faire des fiches ultra détaillées
   - Afficher des fiches differentes en fonction du type de donnée
 - Implémentation d'un router
   - Le router doit permettre d'accèder à n'importe quelle fiche
   - Il peut permettre d'accèder directement au résultat d'une recherche
 - Implémentation d'un système de filtre
   - Mettre en place un système de filtre par type de donnée (personnage, vaisseau, ...)
 - Utilisation de Redux
 - Utilisation du fonctionnel et de l'immutabilité
 - Mise en place de CSS modules

#### Bonus
Malgré les tensions entre l'Empire et le peuple Wookie, il est étonnant de trouver dans leur base de données un moyen de traduire dans cette langue.

 - Permettre d'afficher les résultats en Wookie


Attention, l'utilisation de [swapi-node](https://www.npmjs.com/package/swapi-node) est prohibée, car l'application est surveillée par l'empire. <br/>


Afin que le service de renseignements de l'alliance puisse vérifier l'intégrité de votre code, il sera nécessaire de le rendre disponible sur un repo git accessible.

## Conclusion
Toute l'alliance Rebelle compte sur la réussite de cette mission.

![May the force be with you](https://media.giphy.com/media/JDnaQ8qn0Myuk/200.gif)
