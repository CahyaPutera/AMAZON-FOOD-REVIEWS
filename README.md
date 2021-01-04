# AMAZON-FOOD-REVIEWS

## DESCRIPTION

The dataset used are from : https://www.kaggle.com/snap/amazon-fine-food-reviews.

This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all 500 thousand reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

Since the process on this notebook (especially the model training part) will take a rigorous amount of time to run only on a normal everyday CPU, I will be using google colab's TPU to accelerate the process a little bit and will only take the short reviews (about 40% of the total data), and further reduce the it, so in the end we only got 20% of the total filtered data, that is about 150 thousand data. 

To further see the **pyLDAvis visualization** please open the colaboratoty instead.

## REFERENCES

LDA steps and method :

https://towardsdatascience.com/evaluate-topic-model-in-python-latent-dirichlet-allocation-lda-7d57484bb5d0

Method to find optimal number of topics :

https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/#14computemodelperplexityandcoherencescore


More on visualization with pyLDAvis :

https://github.com/bmabey/pyLDAvis and

https://speakerdeck.com/bmabey/visualizing-topic-models
