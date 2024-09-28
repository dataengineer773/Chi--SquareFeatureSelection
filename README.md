The scikit-learn libarary an implementtation of the chi-square test in the chi2() function,   this function can be used in a feature selection strategy such as selecting the top k most relevant features(largest values) via the
SelectKBest class, we can define the SelectKBest class to use the chi2() function and select all features. then transform the train and test sets and in the next step we print  the score for each variable and plot 
the scores for each variable as a bar graph to get an idea of how many features we should select.
