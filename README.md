# NLP

1. [Word2Vec](./HW2_fullcode_220.ipynb): Word Embeddings with pytorch on Wikipedia biographies data.

-  Leveraging PyTorch’s Embedding class for word2vec to keep track of our target word and context word embeddings.
-  Implemented Skip-gram negative sampling (SGNS), rare word removal and frequent word subsampling to optimize the network.
-  Used tensorboard to log how the model performs
-  Quantified word similarities with cosine similarity measurement
-  Debiasd word2vec with respect to gender bias via implementing penalty function on the loss function
-  
2. [Music genre classification based on lyrics](./  ): 
Modeling: 
- Two language representation models for multi-label genre classification based on song lyrics. To further improve the performance of models on highly imbalanced data
- Three balancing strategies combined with language models are constructed for comparison.
Experimental results:
- BERT models overall give better performances than DistilBERT models. The best BERT model gives a micro F1 of 0.82 and overall accuracy of
67.5%. 
- Balancing strategies can also help model give better performance, especially when combined with DistilBERT model
- The best DistilBERT model with WeightedSampler can give a comparable performance as the best BERT model, while only takes half of time for training compared to BERT models.
