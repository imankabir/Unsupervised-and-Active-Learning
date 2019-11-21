# Unsupervised-and-Active-Learning

#### Supervised, Semi-Supervised, and Unsupervised Learning on Breast Cancer Wisconsin Diagnostic Dataset

- Perfomed Monte Carlo simulation on L1 Penalized SVM supervised learning algorithm.

  - Evaluated model using average accuracies, precision, recall, F-score, ROC, AUC, and confusion matricies
  
- Performed Semi-supervised learning/self-training by splitting the data as labeled and unlabeled
  
  -Used a L1 Penalized SVM to classify labeled data and using distance of unlabelled data point from decision boundary to classify
  
    - Evaluated model using average accuracies, precision, recall, F-score, ROC, AUC, and confusion matricies
    
 - Performed unsupervised learning k-means with k = 2 algorithm. 
    
    - Labeled data by taking a majority vote in the clusters to label the data
    
    - Evaluated model using average accuracies, precision, recall, F-score, ROC, AUC, and confusion matricies

- Implemented spectral clustering using a RBF kernel 


#### Active Learning using SVM on banknote authentication dataset

- Trained a SVM with a pool of 10 randomly selected data points using a linear kernel and L1 penalty.
    
    - Selected L1 parameter via 10 fold CV
    
    - Implemeted passive leaning by iteratively randomly adding 10 data points until all data points were used
    
    - Implemented active learning by iteratively adding 10 data points that were closest to the decision hyperplane until all the data points were used
    
