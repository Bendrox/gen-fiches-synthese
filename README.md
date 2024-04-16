# LLM_SFCR_exploit_Langchain_Azure

L'exercice a pour objectif l'exploitation de données SFCR (Rapport sur la solvabilité et la situation financière) pour l'analyse des organismes d'assurance en utilisant un modèle LLM.

Ce rapport (entre 30 et 80 pages) contient de nombreuses informations sur la situation financière des entreprises d'assurance et sur leur solvabilité et souvent exploité par les parties prenantes (actionnaires, détenteux de capitaux, banques, institutions publiques...) pour la prise de décision.

L'objectif est d'extraire les informations de facon synthétique et pertinance en fonction de 7 axes d'analyse suivants :

Présentation de l'assureur (histoire, secteurs d'activités, pays présents)
Résultat (chiffre d'affaire, résultat d'exploitation, résultat financier, résultat net...)
Provisions (provisionnement...)
Solvabilité (ratio de solvabilité, CSR...)
Gouvernance (mandats, nouvelles nominations de dirigeants...)
Perspectives (stratégie de développement, évolution de l'activité...)


Modèle LLM utilisé : GPT OPENAI

Cloud : Microsoft Azure

Framework: LangChain

Résultats des travaux :
- Les résultats produits par le modèle LLM offrent une base de travail de qualité satisfaisante et constitue une base suffisament pertinante pour permettre à un analyste d'effectuer son analyse.
- Le prompt engineering a un impact significatif sur la qualité des résultats mais aussi sur le temps de traitement du modèle et donc sur le cout des requetes.
- Le traitement de deux rapport simultanés pour la production d'une fiche de synthèse ne permet pas d'avoir des résultat probant. Le modèle semble mélanger les informations malgré les instructions dans le prompt.

Pistes de développement a venir: 
- Essayer d'autres types d'architectures.
- Amélioration de l'extraction de données , notamment via l'exploitation des tableaux dans les rapports et les graphiques
  
