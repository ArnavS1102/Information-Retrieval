# Information-Retrieval Lab Assignments
## **Zipf's Law**
- Pride and Prejudice from Gutenberg project was cleaned and lemmatized.
- A python dictionary was created to store a word and it's frequency.
- A rank was assigned to each word on the basis of it's frequency. Zipf's law was analysed using this rank.
- This analysis was further simplified to a plot.

## **Kibana, Elastic Search and Mean Average Precision**
- Uploaded the document in elasticsearch’s port.
- Used elasticsearch’s API search for getting documents relevant to a query.
- For all the queries, fired a request to get the list of most relevant documents varying the weights from (0,0) to (10,10) for title and data fields each.
- For each query Average Precision for these 10 returned documents was calculated for each weight ranging from (0,0) to (10,10).
- The average precision of a particular weight was added for all the queries and the final sum was divided by the total number of queries to obtain the mean average precision(MAP).
- Maximum MAP and the weights used to obtain it were then studied.

## **Naive Bayes, Rocchio and k-nearest neighbor**
- Extracted the train and test data from the news20 dataset.
- TF-IDF scores calculated.
- Naive Bayes, KNN and Rocchio Classifers trained on this data.
- Classification metrics analysed to determine the best classifier.

## **Latent Semantic Indexing**
- 5 sentences were chosen and tokenized.
- A tf-idf scores matrix was formulated
- A query term's similarity to a document was found with the help of dot product.
- The document which returned maximum similarity was the most relevant document to the query.
## **K-means and Hierarchical Clustering**
- From Reuters-21578 corpus, eliminated documents not in [acquisitions, corn, crude, earn, grain, interest, money-fx, ship, trade, and wheat].
- Cleaned data and calculated tf-idf scores sparse matrix.
- This sparse matrix was fed to K-Means clustering algorithm and Agglomerative Clustering Algorithms(GAAC,single link,complete link and centroid link).
- Plotted a dendrogram and calculated purity scores for each algorithm.

## **Support Vector Machine**
- IRIS dataset was used. "Iris-virginica" and "Iris-versicolor" were used because the assignment required non-linearly separable datapoints.
- Data fitted on several SVM kernels(Linear, Polynomial and Gaussian).
- News20 dataset used to compare classification accuracy of SVMs with KNN,Rocchio and Naive Bayes classifiers.

## **Concept Lattice**
- 5 sentences chosen.
- Extracted all the unique words from these sentences. The number was limited to 20 to avoid a fussy lattice diagram.
- Made a table of occurrences of each word in a tweet.
- Made a visualisation for a concept lattice of this data.

