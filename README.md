# Enquete sur le Baromètre de la DREES - Chapitre pauvreté et exclusion

![alt tag](https://github.com/capucinescspo/Enquete_viesocialedesdonnees/blob/main/visuel.png?raw=true)

## Introduction

La base de données choisie provient du Baromètre d'opinion de la DREES (Direction de la recherche, des études, de l'évaluation et des statistiques) pour l’année 2020. Ce baromètre d’opinion existe depuis 2000 et sonde les français sur différentes thématiques : 
- Inégalités : inégalités de revenus, inégalités entre hommes et femmes, justice sociale, etc.
- **Pauvreté, chômage et exclusion**: évolution de la pauvreté, définition des personnes en risque d’exclusion, opinion sur le montant et l’efficacité du RSA et des allocations chômage, etc.
- Logement : résidence principale, critères d’attribution des logements sociaux.
- Protection sociale : financement de la protection sociale, ciblage des prestations sur les plus modestes ou les seuls cotisants, etc.

## A quoi sert le Baromètre ?
Cet outils permet d'appréhender l’évolution de l’opinion des Français sur les politiques dont les ministères ont la charge, tant en matière de santé que de solidarité. 

Parmi ces thèmes, nous avons choisi de nous concentrer sur la **pauvreté et l’exclusion**. La base de données est traitée pour en tirer des enseignements présentés dans un article : [https://drees.solidarites-sante.gouv.fr/sites/default/files/2021-06/ER1195.pdf](https://drees.solidarites-sante.gouv.fr/sites/default/files/2021-06/ER1195.pdf)

**Nous trouvons pertinent d’analyser cet article et les conclusions proposées, par rapport au contenu initial de la base de données.**


## Édition 2020 du Baromètre et sa construction de l’échantillon

En 2020, 4 002 personnes ont été interrogées dans toute la France métropolitaine. Cet échantillon est construit selon la méthode des quotas, par sexe, âge, profession de la personne de référence, après stratification par région et catégorie d'agglomération. Il est intéressant de noter que les mêmes questions sont posées depuis 2000, dans l’objectif de faire de ce baromètre un **outil de référence**, permettant d’apporter un **éclairage complémentaire** aux travaux existants. Bien que la taille de l’échantillon ait pu varier (3000 personnes interrogées entre 2014 et 2019), le caractère systématique et l’ancienneté du baromètre permet, selon la DREES, d’appréhender l'évolution des opinions sur des politiques publiques du ministère des Solidarité et de la Santé. 

En 2020, l’enquête s’est déroulée du 19 octobre 2020 au 4 janvier 2021, ce qui situe son lancement sept mois après le début du premier confinement et à une période où l’idée d’une « seconde vague » épidémique était très présente dans l’espace public.

Bien qu’il soit difficile d’évaluer précisément les conséquences du contexte sanitaire sur le déroulement de l’enquête, les enquêteurs n’ont pas signalé de difficulté particulière sur le terrain, hormis des contretemps plus importants pour l’obtention des rendez-vous à l’approche des fêtes de fin d’année.

Ce baromètre se distingue de l’indicateur de pauvreté relative en **“définissant la pauvreté par la manière dont elle est perçue, notamment socialement, par les interrogés."** 


## Analyse des résultats du baromètre 2020 dans le document `Un sentiment de pauvreté en hausse chez les jeunes adultes fin 2020´

Dans le contexte de la crise sanitaire, la part des personnes qui jugent leur situation globalement mauvaise s’accroît, notamment parmi les travailleurs indépendants, les jeunes adultes et dans les agglomérations de plus de 100 000 habitants. Les jeunes ressentent : 
- une dégradation de leur situation sur de multiples aspect,
- une préoccupation stable face à la pauvreté et au chômage, 
- une inquiétude croissante envers l’avenir, 
- un sentiment de déclassement intergénérationnel marqué. 

Plusieurs graphiques dans l'article indiquent différentes situations : pauvreté et risques perçus selon l’âge, la CSP, le niveau de vie, impact de la crise sanitaire d’un point de vue financier, ou encore, sentiment de vulnérabilité face au chômage. 

Les données sont présentées de manière exhaustive en datavisualisation à cette adresse : [https://odin.sante.gouv.fr/dataviz_drees/?defaultPage=Baromètre_d_opinion_Baromètre_d_opinion&user=dataviz_sante&pass=dataviz_sante#6](https://odin.sante.gouv.fr/dataviz_drees/?defaultPage=Baromètre_d_opinion_Baromètre_d_opinion&user=dataviz_sante&pass=dataviz_sante#6)


## Critiques sur la collecte des données

Il est intéressant de s’interroger sur la méthodologie employée pour parvenir aux conclusions présentées dans l’article. Ainsi, nous sommes partis de la base de données pour retracer la réflexion qui a mené aux conclusions finales générales. Plusieurs points en sont sortis : 

Le premier point débattu est la pertinence des données : Comment les questions ont été choisies ? La répétition des mêmes questions d’une année à l’autre ne constitue-t-elle pas un obstacle à la représentativité des situations ? En effet, pour un indicateur qui se veut fiable, on comprend une nécessaire continuité, or celle-ci semble ne pas laisser place à des impacts conjoncturels possibles. Par ailleurs, certaines questions semblent porter un jugement non-exploitable dans l’article final tel que « Trouveriez-vous normal qu’on demande aux personnes qui touchent des allocations chômage… » ou encore « Si des personnes se trouvent en situation d’exclusion ou de pauvreté, c’est parce qu’elles ne veulent pas travailler ? Manquent de qualifications ? … ». La question PE6_CD_3 illustre parfaitement notre remarque : 

![alt tag](https://github.com/capucinescspo/Enquete_viesocialedesdonnees/blob/main/PE6_CD_3.png?raw=true)

Une deuxième limite, étroitement liée au choix et à la formulation des questions, est leurs aspects strictement économiques. En effet, pour un indicateur censé venir apporter une complémentarité aux outils existants, en donnant une dimension qualitative, de “ressenti”, de “perception de la pauvreté", de nombreuses questions reposent sur des données strictement financières, les questions sont surprenantes. 	Ainsi, une majorité de questions portent sur des indicateurs très précis : 
- augmentation ou non du RSA, 
- allocations chômage, 
- montant du SMIC,...

Ces interrogations impliquent une certaine culture financière (notamment chez des jeunes surreprésentés dans l’article) pour y répondre de manière précise et représentative.

Enfin, de manière plus générale, les questions portent sur un champ très ciblé, et seules quelques questions sont ouvertes et concernent les individus personnellement (telle que “pourriez vous faire face à une dépense imprévue de 500€ demain?”, expliquant les conclusions sur la « perception » de la pauvreté. L’essence même du baromètre étant de s’éloigner des considérations strictement économiques des indicateurs existants, pour percevoir l’aspect social de la pauvreté, celui-ci paraît surreprésenté dans l’article par rapport aux questions qui y sont réellement liées.

## Interprétation et exploitation des données

Le travail des chercheurs est de transcrire de ce questionnaire de plus de 120 questions des résultats lisibles et pertinents. Cela nous  amène d’emblée à nous questionner sur l’utilisation de l’article : à qui est-il destiné ? doit-il amener à certaines conclusions plus qu’à d’autres? A travers quel prisme? (Envisagée comme une enquête d’opinion pour l’acceptabilité d’une politique publique par exemple). Il semblerait que la DREES soit le principal destinataire et utilisateur de ces données, point que nous allons soulever dans un entretien avec une chercheuse. Par ailleurs, nous avons été particulièrement étonnés du caractère généralisant de l’article dont les conclusions semblent à grande portée, et représentative de l’ensemble de la population. L’échantillon reste de 4 000 personnes. En particulier, les jeunes semblent surreprésentés dans l’article, alors qu’il reste une part relative du questionnaire, et ne sont pas un public ciblé pour les questions qui les concernent. Or, l’article semble mettre en avant une prépondérance de la vulnérabilité des plus jeunes et de leur perception de déclassement et de pauvreté. 

![alt tag](https://github.com/capucinescspo/Enquete_viesocialedesdonnees/blob/main/Graphdeclassement.png?raw=true)

S’il est pertinent de déduire un ressenti particulier chez les jeunes de par leurs réponses alignées au sein d’un échantillon établi selon la méthode des quotas, nous avons jugé intéressant de regarder quelles questions les concernent réellement. Une seule question porte sur les jeunes de 18 à 29 ans:

![alt tag](https://github.com/capucinescspo/Enquete_viesocialedesdonnees/blob/main/PE4_AB_1.png?raw=true)

De la même manière, face à la précision des questions, nous avons cherché à comprendre d’où provenait la “situation mauvaise actuelle” et ce qui était impliqué derrière ce terme. Là encore, seule une question semble y faire précisément allusion (question PE15_AB):

![alt tag](https://github.com/capucinescspo/Enquete_viesocialedesdonnees/blob/main/PE15_AB.png?raw=true)

La vaste majorité des questions portent réellement sur des connaissances du montant des aides disponibles (allocations, RSA, SMIC…), et ne permettent pas d’en déduire selon les réponses une situation “mauvaise”. 

A contrario, la tendance générale d’inquiétude croissante face à l’avenir, soulignée par l’article, semble soutenue par une variété de questions permettant de sonder ce sentiment “d’inquiétude”, très qualitatif et peu quantifiable par des indicateurs économiques. Cependant, il aurait été intéressant de voir si cette inquiétude croissante était liée au Covid-19, ou non. L’addition de “depuis la crise du Covid” permet dans une certaine mesure de mesurer un potentiel écart de réponses, mais il serait intéressant de pousser la réflexion plus loin et d’observer si ces réponses retournent à la “normale” dans le baromètre 2021, ou s’il permet de constater des effets de long-termes sur l’inquiétude des gens post-covid. Ainsi, les questions ci-dessous illustrent la mesure de l’inquiétude croissante relevée sur des situations individuelles ou des ressentis généraux sur la pauvreté et l’exclusion :

![alt tag](https://github.com/capucinescspo/Enquete_viesocialedesdonnees/blob/main/PE18_CD.png?raw=true)

![alt tag](https://github.com/capucinescspo/Enquete_viesocialedesdonnees/blob/main/PE2.png?raw=true)

Ainsi, nous pouvons voir que certaines des grandes tendances dégagées par l’article semblent s'éloigner de la réaction du sondage, à l’exception de certains points. Par ailleurs, le graphique final indiqué dans l’article prouve bien qu’il s’agit d’un exercice d'interprétation et de classification des répondants pour faire parler des chiffres “forts”.En effet, une nouvelle lecture est proposée aux prisme des CSP, du niveau de vie, ou encore du risque perçu, autant d'interprétations possibles que de catégories de répondants.

![alt tag](https://github.com/capucinescspo/Enquete_viesocialedesdonnees/blob/main/Graphique_étoile.png?raw=true)

C’est donc dans l’optique de confronter notre analyse critique à l’expertise du questionnaire, que nous avons échangé avec Mme Claudine Pirus, chercheuse à la DREES, ayant rédigé un des 3 articles découlant du baromètre 2020. 


## Entretion avec la DREES

![alt tag](https://github.com/capucinescspo/Enquete_viesocialedesdonnees/blob/main/itw1ok.png?raw=true)
![alt tag](https://github.com/capucinescspo/Enquete_viesocialedesdonnees/blob/main/itw2ok.png?raw=true)
![alt tag](https://github.com/capucinescspo/Enquete_viesocialedesdonnees/blob/main/itw3ok.png?raw=true)

Enquête menée par Eva Lecomte, Felipe Lopez de Aréchaga & Capucine Ulian
