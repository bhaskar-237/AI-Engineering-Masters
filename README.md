# Data-Science-Projects
Collection of Data Science Projects

# [Project 1: Sentiment Analysis of Companies from Newspaper Headlines](https://github.com/Jlod95/Data-Science-Projects)
* Scrapped Finviz website for headlines using Beautiful Soup
* Used nltk to carry out sentiment analysis on headlines
* Used pandas and matplotlib to visualise the data

# [Project 2: EDA with Python and Logistic Regression - Titanic](https://github.com/Jlod95/Data-Science-Projects/blob/main/EDA%20with%20Python%20and%20Logistic%20Regression%20-%20Titanic.ipynb)
* Simply project for practicing EDA and Data Visualisation techniques
* Used Logistic Regression Model. Logistic model is just Linear Regression under a transform, usually a Sigmoid function
* It is used when we want to examine a binary dependent variable relationship with one or more independent variables
* Used a classification report as well, which contains precision, recall, f1-score
* Precision is a good evaluation metric to use when the cost of a false positive is very high
* Recall calculates the percentage of actual positives a model correctly identified
* The  F1-score, is a measure of a model's accuracy on a dataset, it is a combination of precision and recall, and would be most appropriate in this case

# [Project 3 - Feature Selection - ANOVA & Chi-Squared](https://github.com/Jlod95/Data-Science-Projects/blob/main/Project%203%20-%20Feature%20Selection%20-%20ANOVA%20%26%20Chi-Squared.ipynb)
* We want to see if there is a difference in average time depending on what variable we are interested in
* We are dealing with more than 3 variables (groups)
* If we were dealing with only two groups and wanted to see if there is a difference in average time between them we would use t-test usually. However, for three or more variables, we use ANOVA (Analysis Of Variance) 
* ANOVA is perfect for analysing categorical variables affect on a numerical variable
* For thwe second task, we are dealing with a categorical independent variable and categorical dependent variables (more than 2)
* For this case we use Chi-Squared
* In both instance, we can use scipy packages, which saves a lot of time and work
* Also in both cases the p-value is almost zero, that is to say there is an almost zero percent chance of this dataset occuring if the null hypothesis is true
* From that, in both cases we can say that we reject the null hypothesis. 
* In the first case that means we can say the complaint type does affect the response time
* In the second case that means we can say the location does affect the type of complaints one can expect to receive from there
