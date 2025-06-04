# LLM_SFCR_exploit_Langchain_Azure

## Objectif:  
Exploiter les remises narratives réglementaire (SFCR - Rapport sur la solvabilité et la situation financière) pour produire une fiche d'analyse des organismes d'assurance structurée en plusieurs axes: 

- Présentation de l'assureur (histoire, secteurs d'activités, pays présents)
- Résultat (chiffre d'affaire, résultat d'exploitation, résultat financier, résultat net...)
- Provisions (provisionnement...)
- Solvabilité (ratio de solvabilité, CSR...)
- Gouvernance (mandats, nouvelles nominations de dirigeants...)
- Perspectives (stratégie de développement, évolution de l'activité...)

## Source de données: 
Les données sont dans des rapports réglementaires (entre 30 et 80 pages) qui contiennent de nombreuses informations sur la situation financière des entreprises d'assurance et sur leur solvabilité et souvent exploité par les parties prenantes (actionnaires, détenteux de capitaux, banques, institutions publiques...) pour leur prise de décision.


## Outils: 
- Python 
- Modèles OpenAI
- Cloud Azure 
- Frameworks: LangChain

## Résultats:
- Les premiers résultats offrent une base de travail de qualité satisfaisante et constitue une base suffisament pertinante pour permettre à un analyste d'effectuer son analyse.
- Le prompt engineering a un impact significatif sur la qualité des résultats mais aussi sur le temps de traitement du modèle et donc sur le cout des requetes.


##  To do : 
- Essayer d'autres types d'architectures.
- rajouter comparatif N vs N-1
  
