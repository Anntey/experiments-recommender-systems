## Recommender systems

1. Movie recommender based on outgoing wikipedia links that takes as input positive (1) and negative (-1) link-movie matches and learns for the movies and links embeddings that maximize cosine similarity for matches and minimize it for non-matches.

2. Music recommender based on spotify song ids. Feeds lists of songs ids to a word2vec model. A 'sequence' is a list of songs ids in a particular playlist. Songs that are present in the same playlist should be similar because they have the same context.
