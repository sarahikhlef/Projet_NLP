# Projet NLP 

## Réalisé par: 
- Sarah IKHLEF
- Brahim BERKENNOU
  
## Objectif : 
Mettre en œuvre des techniques de Traitement Automatique du Langage Naturel (TALN) pour effectuer à la fois l'analyse de sentiment et la classification de sujets de manière efficace.

## Dataset : 
- Disponible sur : https://huggingface.co/datasets/financial_phrasebank/
- Contient des phrases financières annotées.
- Les annotations indiquent le sentiment associé à chaque phrase, comme positif, négatif ou neutre,ce qui en fait un ensemble de données adapté à l'entraînement de modèles d'apprentissage automatique pour la classification de sentiment dans le contexte financier.

## Techniques utilisées : 

- #### Sentiment Analysis:
   - Approche classique :
       -  Prétraitement des données : BOW, TF-IDF, Word2Vec
       -  Entrainement :  LogesticRegression, Random Forest, XGBoosting, SVM
   - Transformers : BERT , AlBERT, RoBERTa
- #### Topic Modeling:
   - Approche classique : LDA, NMF
   - Transformers : Bert Topic 
