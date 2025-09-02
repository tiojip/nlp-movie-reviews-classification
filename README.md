# nlp-movie-reviews-classification
Projet académique – Classification de critiques de films avec Naive Bayes (unigrammes, bigrammes, trigrammes). Prétraitement, classification et interprétation des termes discriminants.

## Approche
- Prétraitement : nettoyage, tokenisation, stopwords (NLTK)
- Représentation : sac de mots, n-grammes
- Modèles : Naive Bayes (uni/bi/tri-grammes)
- Interprétation : termes discriminants positifs/négatifs

## Contenu
- `notebooks/` : expérimentation et analyse

## Résultats
- Accuracy améliorée avec les **bigrammes**
- Mise en évidence des termes les plus discriminants

## Reproduire
```bash
pip install -r requirements.txt
jupyter notebook notebooks/nlp_movie_reviews.ipynb
