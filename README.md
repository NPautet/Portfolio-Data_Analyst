# Portfolio Data Analyst


Bienvenue sur le dépôt GitHub de mon portfolio de Data Analyst. Vous trouverez dans ce dépôt les différents projets que j'ai réalisés dans le cadre de ma formation avec OpenClassrooms au cours de l'année 2025. Ces projets couvrent les aspects essentiels du métier de Data Analyst.

Les projets réalisés illustrent mes compétences-clés comme l'analyse de données, la visualisation de données (grâce à des bibliothèques graphiques et des tableaux de bord), ainsi que la modélisation, la création et la manipulation de bases de données. Lors de cette formation, j'ai découvert ou amélioré ma maîtrise des outils Data comme Python (bibliothèques Pandas et sklearn), SQL, Excel et Power BI.


## Principaux projets réalisés

### [P07 - Créer un tableau de bord dynamique avec Power BI pour visualiser l'avancement de projets](https://github.com/NPautet/Portfolio-Data_Analyst/tree/main/P07_Sanitoral)
![Power BI](https://img.icons8.com/color/48/000000/power-bi.png)


En tant que Data Analyst consultant, je suis chargé de mettre en place pour une entreprise cliente un tableau de bord permettant de suivre l'avancement de ses projets à l'international au travers de 3 KPIs, concernant le suivi temporel des plannings, les coûts engagés et le nombre de livrables réalisés. Le but est de construire un outil dynamique, destiné à des utilisateurs n'ayant pas les mêmes droits d'accès aux données, et qui ont des attentes différentes vis-à-vis de l'outil.

Tâches réalisées :
- Identification des besoins des utilisateurs 
- Explicitation des *User Stories* dans un *Product Strategy Canvas* (démarche de design)
- Préparation des données
- Création de mesures DAX personnalisées
- Développement de visualisations répondant aux *User Stories*
- Production de reportings avec différents niveaux de granularité pour faciliter la prise de décisions à différents niveaux hiérarchiques

![Screenshot](screenshots/Dashboard_P7.png)

### [P05 - Créer une base de données immobilière avec SQL](https://github.com/NPautet/Portfolio-Data_Analyst/tree/main/P05_DATAImmo)
![SQLite](https://skillicons.dev/icons?i=sqlite)

En tant que Data Analyst dans un réseau national d'agences immobilières, il m'a été confié de mettre en place une base de données permettant de collecter les données de transactions immobilières en France. Cette base de données m'a ensuite servi à analyser le marché sur une période donnée pour aider les agences régionales à mieux accompagner leurs clients.  

Tâches réalisées :  
- Création d'un modèle de données (MCD puis MLD) cohérent avec les besoins métiers et en respect du RGPD
- Création d'une base de données en respect des bonnes pratiques (normes 3NF) et des besoins clients
- Requêtes SQL avancées pour répondre à une problématique métier


### [P08 - Analyser les indicateurs de l'égalité professionnelle femmes/hommes en respect du RGPD](https://github.com/NPautet/Portfolio-Data_Analyst/tree/main/P08_%C3%89galit%C3%A9Pro_FH)
![KNIME](https://img.shields.io/badge/KNIME-FFD800?style=for-the-badge&logoColor=black)

Je suis en charge d'automatiser la création d'un rapport sur l'égalité professionnelle femmes/hommes au sein de mon entreprise, en utilisant le logiciel de programmation visuelle (no code) KNIME, via la mise en place d'un workflow complet à partir de données RH des salariés de l'entreprise. Ce workflow doit permettre de produire un rapport détaillé expliquant le score obtenu pour chaque indicateur de l'index global, ainsi que des graphiques pertinents expliquant de façon visuelle les potentielles pistes d'amélioration du score de l'index global.

Tâches réalisées : 
- Création d'un workflow complet de traitement des données conforme aux textes légaux
- Collecte des données pertinentes dans le respect des normes et bonnes pratiques (RGPD)
- Agrégation des extractions de données en définissant les règles de nettoyage pour chaque indicateur
- Vérification de la cohérence et la fiabilité des données préparées pour chaque indicateur
- Production de visuels explicatifs proposant des pistes d'amélioration du score de l'index

### [P09 - Analyser les ventes d'une librairie avec Python](https://github.com/NPautet/Portfolio-Data_Analyst/tree/main/P09_Ventes_Librairie)
![Skills](https://skillicons.dev/icons?i=python)

En tant que Data Analyst pour une librairie en ligne, je dois produire une analyse des KPIs des ventes et essayer d'établir des segments clients cohérents à partir des données de ventes.

Tâches réalisées : 
- Analyse de séries temporelles
- Tests statistiques sur les données afin de tester et valider des hypothèses quant au lien entre certaines variables

### [P11 - Produire une étude de marché avec Python](https://github.com/NPautet/Portfolio-Data_Analyst/tree/main/P11_%C3%89tude_march%C3%A9_Poulet)
![Skills](https://skillicons.dev/icons?i=python)

En tant que Data Analyst dans une entreprise française qui commercialise de la viande de poulet, je dois produire une étude de marché pour identifier de potentielles opportunités commerciales à l'international. J'ai une totale liberté sur les données avec lesquelles je peux travailler, si ce n'est la cohérence et la pertinence de ma démarche (méthode PESTEL). Je dois identifier, collecter, nettoyer et analyser les données pour les pays du monde, puis regrouper les opportunités en clusters.

Tâches réalisées :
- Définition des données étudiées par la méthode PESTEL
- Collecte et nettoyage des données
- Réalisation d'analyses bivariées pour comprendre la corrélation entre les variables
- Réalisation d'une Analyse en Composantes Principales (ACP) pour réduire la dimension du jeu de données et optimiser le temps d'apprentissage des modèles
- Utilisation et comparaison de plusieurs méthodes de clustering pour segmenter les ooportunités

![Screenshot](screenshots/Clusters_P11.png)

### [P12 - Détecter des faux billets avec Python](https://github.com/NPautet/Portfolio-Data_Analyst/tree/main/P12_Faux_Billets)
![Skills](https://skillicons.dev/icons?i=python)

Je travaille pour une organisation institutionnelle, l'Organisation Nationale de lutte Contre le Faux-Monnayage (ONCFM). J'ai pour mission de tester, d'optimiser et de comparer des modèles prédictifs supervisés permettant d'authentifier (ou non) des billets de banque à partir de leurs mesures géométriques.

Tâches réalisées :
- Analyse des distributions des variables selon l'authenticité des billets
- Utilisation et comparaison de modèles de régression linéaire pour imputer les valeurs manquantes du dataset
- Mise en œuvre de modèles d'apprentissages supervisés pour réaliser des prédictions
- Comparaison des modèles prédictifs étudiés par validation croisée et grâce à la définition d'une métrique pertinente
