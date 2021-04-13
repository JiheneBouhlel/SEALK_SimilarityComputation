# SEALK_SimilarityComputation
## Additional Questions

### 1. What would you change if the list of companies was much larger (several millions) ?

  Si nous disposons d'un jeu de données plus large, j'utiliserais la méthode LSH "Locality sensitive hashing" qui consiste à trouver les voisins les plus proches afin d'eviter le probleme de la malédiction de la dimension.
  
### 2. Which distance would be more suitable to this problem if topics had scores ?
  Si les topics ont des scores, la similarité cosinus sera plus approprié que la distance de Jaccard.
  
### 3. What libraries, techniques or algorithms would you have chosen if there were no restrictions.
Parmi les librairies possibles, scikit-learn pour nous fournir les methodes tf-idf, CountVectorizer pour transformer les données textuelles en numériques, et aussi les algorithmes tels que cosine_similarity et jaccard_score.
C'est possible aussi d'utiliser la librairie scipy qui nous fournit les algorithmes pour clculer les distances.
