## Week4 Topics:
* Word count representation for measuring similarity
  - Bag of words model
    - Disadvantage: Rare words are not addressed
  - TF-IDF: Prioritizing important words
    - Upweight words that are frequent in the document but not corpus
    - Downweight words that are frequent in the document but also in the corpus
    
* Distance metrics:
  - Euclidean Distance(scaled,non-scaled)
  - Cosine similarity
    * Cosine similarity allow us to capture the similarity of docus even if their size differ a lot
    * Cosine is essentially the same as Euclidean distance on normalized data
* Retrieving similar documents
  - 1NN
  - KNN
  
* Clustering similar documents
  - known labels: multi-classification problem
  - unknown labels: unsupervised learning problem using k-means algorithm
  

## Algorithms: 
* Bag of words, TF-IDF
* K-means





## Implementation Details of Programming Assignment:
* Execute document retrieval code with the Jupyter notebook
* Load and transform real, text data
* Compare results with word counts and TF-IDF
* Set the distance function in the retrieval
* Build a document retrieval model using nearest neighbor search

