# XAI_topic_modeling
## Document’s topic as explaining features for text classifier
### Explainable AI Seminar Final Project, Technion 096290

### Movie genre classification - CMU Movie Summary Corpus
Top2vec topic model generates topics 
Model’s document embedding are used as tabular features input to random forest and logistic regression classifiers, accompanied with LIME explanations.
Topics also used as post-hoc explainers to random forest classifier with full text input.

### Aspect based sentiment analysis (ABSA) - SEMEVAL2014 restaurant reviews
use ABSA a proxy method to interpret document-level sentiment DLSA
