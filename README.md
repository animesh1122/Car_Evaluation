# Car_Evaluation


# DATA
     Dataset can be found on UCI Machine Learning website  http://archive.ics.uci.edu/ml/datasets/Car+Evaluation.
     
  Attribute Information: 6 features and 1 class variable.

    Class Values:

    unacc, acc, good, vgood

    Attributes:
    
    buying: vhigh, high, med, low.
    maint: vhigh, high, med, low.
    doors: 2, 3, 4, 5more.
    persons: 2, 4, more.
    lug_boot: small, med, big.
    safety: low, med, high.
    
# TASKS

#    Train the classifiers using the first 1600 instances. Test the trained classifiers on the remaining instances.
#    Data Cleaning: Handle the missing feature values (e.g., remove missing features, use mean or median value or fill the most popular value).
#    Classification Part:
      Use three classifiers: 
      (1) Naïve Bayes 
      (2) ID3 Decision Trees 
      (3) Random Forest
#    Per class classification accuracy, and confusion matrix to compare the results.
#    Compare the accuracies of the classifiers when trained on first 500, 750, and 1250 instances and always reserving the last 200 instances for testing. 
