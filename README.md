# Complete Feature_Selection
# SUMMARY

We can summarize feature selection as follows.

__Feature Selection:__ Select a subset of input features from the dataset.

* __Unsupervised:__ Do not use the target variable for selecting the feature importance of Input variable (e.g. remove redundant variables).

     * Correlation
     
* __Supervised:__ Use the target variable (e.g. remove irrelevant I/P features).
      
     * __Wrapper Method:__ Search for well-performing subsets of features.
     
          * Recursive Feature Elimination (RFE)
          
          * Sequential feature Selection
          * Genetic Algorithm
  
     * __Filter Method:__ Select subsets of features based on their relationship with the target.
     
         * Statistical Methods
      
         * Feature Importance Methods
         
         * Information Gain
         
         * Chi-square Test
         
         * Varience Threshold
         
* __Intrinsic:__ Algorithms that perform automatic feature selection during training.
     
     * Decision Trees
     
     
* __Dimensionality Reduction:__ Project input data into a lower-dimensional feature space.
