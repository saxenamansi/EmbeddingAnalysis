# EmbeddingAnalysis

Embedding is vital in natural language processing, converting text to numbers while capturing syn- tax and meaning. It maps data to points in an n-dimensional space, reflecting similarities between instances. This project explores diverse embeddings on a news snippet dataset to identify the reported event.

This project involves two main steps. First, we create an embedding scheme to convert each training instance into an n-dimensional vector. We then utilize the Nearest Neighbor search algorithm using cosine similarity to assess the embedding on the testing data. This way, we find the most similar reports in the training data for each news snippet in the testing set and the Top-1, Top-3, and Top-5 accuracy measures are computed, where Top-n accuracy indicates whether the correct event ID appears within the n most probable events retrieved through ranking the snippets by their likelihood. We propose TF-IDF as the baseline metric and Word2Vec and BERT as the the better proposed approaches.

