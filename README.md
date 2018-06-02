# Classify-food-items-Unsupervised-learning-
I have classified a database of food items into appropriate segments (veg, non-veg, drinks, etc) using an unsupervised approach, since there are no features in our data.

I have used Word2Vec, SpaCy, GloVe and cosine similarity matrices.

Example input: (.csv file)

Item_name
Paneer Wrap
whiskey
chicken tikka

Example output: (.csv file)

Item_name             label
Paneer Wrap            veg
whiskey               alcohol
chicken tikka         non-veg


The actual database contains around 30000 rows.
