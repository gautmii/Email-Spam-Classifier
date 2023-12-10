# Email-Spam-Classifier
Naive Bayes represents a supervised method rooted in Bayes' Theorem, presuming independence among predictors. In simpler terms, it assumes that the occurrence of a specific feature in a class isn't linked to the presence of any other feature.

This technique is widely employed in text categorization, sorting documents into distinct categories (like spam or legitimate, sports or politics) by utilizing word frequencies as features.

Objective: To accurately assign a class to new, unseen records.

The process involves a collection of emails labeled as 'spam' and 'ham' (non-spam), initially stored in a DataFrame. These emails are then processed using CountVectorizer. This data is utilized to train the model, which is subsequently tested for predictions using sample inputs. The Python libraries employed encompass pandas, numpy, io, os, CountVectorizer, and MultinomialNB from sklearn.
