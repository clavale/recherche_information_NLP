# mise en place d'un système  de recherche d'information et analyse de données textuelles

### Auteurs: Adjoua HOUNDONOUGBO and Morel MBEDI

### Ce projet  a été réalisé dans le cadre du cours "network analysis for information retrieval"  de notre formation "Master 2  Machine learning pour l'Intelligence Artificielle" à l'université Lumière Lyon 2


### L'objectif est d'explorer les données textuelles constitué d'un corpus es articles scientifiques afin d'extraire des informations pertinentes: moteur de rechrche,clustering des articles,modélisation thématique (LDA, BERTopic°, visualisation

### Démarches :
- acquisition de données:  Nous allons utiliser le jeu de données provenant des Citations Network Dataset qui rassemble plusieurs millions d'articles: https://www.aminer.org/citation.

  Nous allons utiliser en particulier la version 10 qui comprend 3 079 007 articles et 25 166 994 citations, extraits le 27 octobre 2017

- prepocessing de données textuelles: stopword, lemmatisation,matrice documents terms(TF, TF-IDF, Doc2vec,etc)

- Visualisation et analyse: clustering de documents(tokens),LDA( modèle de modélisation thématique), visulisation des résultats (pyLDAvis)
- modélisation à l'aide d'un graphe de données
- BERTopic: modéle thématique  dit "génératif" qui exploite les transformers et c-TF-IDF (https://maartengr.github.io/BERTopic/index.html)
