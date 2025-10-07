## ADS 509: Topic Modeling

Topic modeling project using the NLTK Brown corpus. Three models are fitted and compared to the corpus’ official categories:

* NMF (with TF-IDF)
* LSA / TruncatedSVD (with TF-IDF)
* LDA (with Count vectors)

# Files
* ADS 509 Assignment 5.1 Topic Modeling.ipynb — main notebook
*  ADS 509 Assignment 5.1 Topic Modeling.pdf — exported report
*  lda_topics_brown.html — interactive LDA visualization (optional)

# Data
Brown corpus categories used: editorial, government, news, romance, hobbies.

# Workflow
*  exploration of corpus and document lengths
*  Vectorization: TF-IDF for NMF/LSA; Count for LDA
*  Comparison to gold categories via cross-tabs and clustering metrics (V-measure, ARI, AMI)
*  Topic visualization with pyLDAvis

# Findings (k = 5)
*  NMF: Moderate alignment with clear themes (news, editorial, romance, hobbies), some overlap between news and government
*  LSA: Weakest alignment, components act as semantic axes that mix categories
*  LDA: Moderate alignment, distinct topics for government/economy, news/politics, narrative/romance, and hobbies
  
