# NLP

1. [Word2Vec](./HW2_fullcode_220.ipynb): Word Embeddings with pytorch on Wikipedia biographies data.

-  Leveraging PyTorch’s Embedding class for word2vec to keep track of our target word and context word embeddings.
-  Implemented Skip-gram negative sampling (SGNS), rare word removal and frequent word subsampling to optimize the network.
-  Used tensorboard to log how the model performs
-  Quantified word similarities with cosine similarity measurement
-  Debiasd word2vec with respect to gender bias via implementing penalty function on the loss function
