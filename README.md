# Topics as explaining features for text classifier
## Explainable AI Seminar Final Project, Technion 096290

### Movie genre classification - CMU Movie Summary Corpus
Top2vec topic model generated topics 
Model’s document embedding are used as tabular features input to random forest and logistic regression classifiers, accompanied with LIME explanations.
Topics are also used as post-hoc explainers to random forest classifier with full text input.

### Aspect based sentiment analysis (ABSA) - SEMEVAL2014 restaurant reviews
use ABSA as a proxy method to interpret document-level sentiment DLSA
