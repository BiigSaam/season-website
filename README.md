# Festival MMI Site web


## Objectif :

Créer un site web afin de concurrencer les participants au festival MMI 2024 dans la partie **“développement web”**

## Idée :

Faire un site web axé sur le thème des saisons avec des informations sur la saison choisie afin d’avoir plus d’interaction et de proposer une expérience utilisateur optimale à nos clients. Vous partirez sur la structure suivante : 

```
code/
├── public/
│   ├── fonts/
│   ├── images/
│        └── Favicons
│   ├── styles/
│   └── includes/
│				├── header.html
│       └── footer.html
├── src/
    ├── index.html
		├── summer.html
		├── autumn.html
		├── winter.html
		└── spring.html
```

## Accessibilité :

Lors de la réalisation de ce projet, il faudra notamment faire attention aux normes d’accessibilité du site web afin de satisfaire l’expérience utilisateur et de le rendre le plus optimale. Il faudra également faire attention à la partie responsive (facultatif).

## `src/`

Expliquons les attentes dans le dossier `src/` : 

### `src/index.html`

Ce fichier est la page d’accueil de notre client. Il devra être composé de : 

- un header
- 4 images emmenant vers la page saison correspondante
- un background correspondant à la saison dans laquelle nous sommes
- la Date actuelle
- un footer
    
    ### Fonction Date :
    
    La fonction date doit permettre à l’utilisateur de connaître la saison au moment où l’utilisateur est dans notre site. Ainsi, au début de chaque page, une bannière doit être là afin de lui signaler la saison actuelle. De plus, le code également doit s’approprier cette interaction en proposant le background adéquat à la saison. 
    
    > *Exemple : 
    Si on est le 5 janvier 2024 (?), l’utilisateur doit avoir sur la bannière de la page accueil le message suivant : “Nous sommes en Hiver“ avec des flocons de neige FICTIFS qui tombent sur le mot hiver, ainsi que la page décoré en mode hiver.*
    > 

### `src/[season_name].html`

Ce fichier est la page présentant la page saison. Il devra être composé d’informations ainsi que de mini jeux sur la saison, le tout en ayant des animations ainsi qu’un background sur le thème également.

Pour la partie information, il faudra collecter des informations sur la saison, mais aussi des anecdotes, et des fêtes/jours fériés arrivant lors de cette saison.

> *Note : Attention toutefois aux normes d’accessibilité, notamment pour le contraste lorsque vous choisissez les couleurs, ou même l’image avec la nécessité de mettre un texte alternatif*
> 

## Sites web pour la collecte des informations :

- **Printemps :**
    - [**Sciences et avenir**](https://www.sciencesetavenir.fr/nature-environnement/printemps-tout-savoir-sur-cette-saison_162322)
    - [**Wikipédia**](https://fr.wikipedia.org/wiki/Printemps)
    - [**Educatout**](https://www.educatout.com/activites/themes/printemps.htm)
    - [**Les débrouillards**](https://www.notion.so/Calculateur-de-notes-ec07355183ad43e698d7cc06a59c7869?pvs=21)
- **Eté :**
    - [**Wikipédia**](https://fr.wikipedia.org/wiki/%C3%89t%C3%A9)
    - [**Le Mag femme**](https://www.lemagfemmes.com/Vie-quotidienne/La-saison-de-l-ete.html)
    - [**Franceinfo**](https://www.francetvinfo.fr/meteo/canicule/infographie-l-ete-une-saison-tout-aussi-meurtriere-pour-les-sdf_981455.html)
    - [**Francebleu**](https://www.francebleu.fr/emissions/n-arrete-pas-l-histoire/l-ete)
    - [**La Désirade**](https://www.hotel-la-desirade.com/anecdotes-de-la-saison-passee/)
- **Automne :**
    - [**Wikipédia**](https://fr.wikipedia.org/wiki/Automne)
    - [**Yahoo actus**](https://consent.yahoo.com/v2/collectConsent?sessionId=3_cc-session_2910ad76-8ae1-48d1-9227-733a765124de)
    - [**La Cour d’Orgères**](https://www.lacourdorgeres.com/saison-automne,pa101.html)
    - [**Aquaportail**](https://www.aquaportail.com/dictionnaire/definition/757/automne)
    - [**Pomverte**](https://www.pomverte.com/themes/saisons/automne/infos)
    - [**Le Point**](https://www.lepoint.fr/sciences-nature/premier-jour-de-l-automne-3-choses-a-savoir-22-09-2015-1967162_1924.php)
- **Hiver :**
    - [**Wikipédia**](https://fr.wikipedia.org/wiki/Hiver)
    - [**Franceinfo**](https://www.francetvinfo.fr/meteo/climat/froid-neige-givre-verglas-qu-est-ce-que-l-hiver-meteorologique-qui-commence-le-1er-decembre_6211527.html)
    - [**Parents**](https://momes.parents.fr/apprendre/matieres-scolaires/sciences/les-saisons/je-decouvre-lhiver-847988)
    - [**MSN**](https://www.msn.com/fr-ca/actualites/other/30-anecdotes-gla%C3%A7antes-ou-pas-sur-l-hiver/ss-AA1l4wZQ)
    - [**Pratique**](https://www.pratique.fr/actu/moscou-paris-brisez-la-glace-avec-ces-4-anecdotes-sur-l-hiver-7396859.html)

## TO-DO List :

- [ ]  Chercher les informations ainsi que des anecdotes drôles/intéressants pour chaque saison
- [ ]  Réfléchir sur les idées de mini-jeux à proposer pour chaque saison
- [ ]  Explorer et faire le choix des couleurs, images pour chaque saison en respectant les normes d’accessibilité
- [ ]  Créer le dossier de code ainsi que les pages
- [ ]  Placer les informations récoltées ainsi que les mini-jeux crées sur les pages correspondantes
- [ ]  Créer des animations js/css pour plus d’interactions
- [ ]  Ajouter une fonction Date
