**K Means Clustering**

    Data - [Generated Data using scikit learn make_blobs]

        - K means algorithm - clustered the data into 4 clusters
        - Compared result visually.
        - Checked with 2, 3, 8 clusters and visualized to get an intuition on KMeans clustering
        
    Data - [College_Data]

        - KMeans Clustering to cluster Universities into to two groups, Private and Public.
        - Some Exploratory Data Analysis done
        - Create 2 Clusters using KMeans clustering Algorithm
        - Since this is a labelled data, we can Evaluate our model. But in general case we wont have this step
        
**PCA**

    Data - [Cancer Data set from Scikit-learn]

        - From 30 attributes in the dataset Find components that are most important and explain the most variance in the dataset
        - Scaled Data (to single unit variance)
        - Features compressed to 2 Principal components
        - Plotted HeatMap to visualise the principal Component vs feature
        
        
**Recommendation System**

    Data - [Movie Lens Dataset]

        - Visualisation done on the dataset
        - Created Pivot table - userid vs title and ratings as data
        - From Pivot table extracted Recommendation for 2 movies (starwars, liarliar)
        - Using corrwith - to get the correlation in ratings for each movies similar to starwars and liarliar
        - "Number of ratings' plays a role - so filtered on 'Greater than 100 ratings'

**Natural Language Processing**

    Data - [Spam sms dataset]

        - Classify whether the sms is ham or spam.
        - Install stopwords from nltk
        - Visualize data - histogram on length of message. Good separation identified
        - Remove punctuation and stopwords from messages
        - Vecorize and get bag of words
        - Term weighting and Normalization done using TfidfTransformer
        - Train using NaiveBayes Classifier Algorithm
        - Use Pipeline on train-test splitted data
        - Predict and evaluate the model
        
   Data - [Yelp]

        - Classify Yelp reviews as rated star 1 or star 5
        - Exploratory data analysis. 
        - Length of text follows same pattern for all stars, so not a good fit for analysis
        - NLP Classification with MultinomialNB
        - Evaluate model
        - Pipeline and evaluate (Not better than the first)
       