# Fuzzy inference system
this is the 4th step in the ADM project which comes after applying GA for featuer selection (https://github.com/satishphale/genetic-feature-selection) followed by discretizing into equibins (https://github.com/abhilashgahankari/ADM_Project) followed by decision tree to get rules (https://github.com/aashitadutta/PerCapitaViolentCrimesPrediction).

matlab is used for the fuzzy inference system. rules from decision tree are configured in fis
main.fis has combination of trapezoidal and triangular membership functions .
trial.fis has triangular membership functions alone.
accurracy.m computes the confusion matrix and gives the accuracy of the model.

with different de-fuzzification techniques we get the below accuracies:
main.fis:
som 		  76.4293
centroid	77.0812
mom			  76.5296
bisector	76.7302
lom			  76.5797

trial.fis :
som 		  75.8655
centroid	76.3673
mom			  75.9659
bisector	75.9659
lom			  62.7195
