# Information-Retrieval
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
## **Latent Semantic Indexing**
## **K-means and Hierarchical Clustering**
## **Support Vector Machine**
## **Concept Lattice**
