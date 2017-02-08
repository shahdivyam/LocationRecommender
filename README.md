# Location Recommender System 

Collabrative-filtering based recommender system

The dataset used for making recommendations to users is taken from FOURSQUARE. The data is processed and each tupple for every user is of the form :
  
  user = (userid , locid , countTotal , rating , distance , Y-Value)
  
To recommend locations or points of Interest(POI's) ‘classification’ algorithms to classify the locations based on the clusters  have been used. For this, I compare support vector machines (SVM), radial basis function (RBF) neural network, and probabilistic neural network (PNN), which are the state-of-the-art algorithms currently used for classification. In addition,  Adaptive Boosting-Gradient (more commonly known as AdaBoost) algorithm, which is a meta-algorithm that combines the result from many weaker decision-tree algorithms into a single strong classifier is introduced.

For every user to whom locations have to be recommended , the complete data for the user should be there in the form specified above. On the basis of that data recommendations are made. 
