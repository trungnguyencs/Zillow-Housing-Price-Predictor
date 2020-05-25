# Zillow Housing Price Predictor

Mini project for Data Science graduate course at Stony Brook University, Fall 2017 
In here, I analyzed a dataset containing information of 2.9 million properties and developed algorithms that makes predictions about the future sale prices of homes

## PART 1: Exploratory Data Analysis

### Task 1
Do a pairwise Pearson correlation analysis on all interesting pairs of variables. Show the result with heat map and find out most positive and negative correlations

### Task 2
Produce five other informative plots revealing aspects of this data. For each plot, write a paragraph in your notebook describing what interesting properties your visualization reveals. These must include:
- at least one line chart
- at least one scatter plot or data map
- at least one histogram or bar chart

### Task 3
Set up a simple linear regression model on one or more variables to predict the logerror as a function of other variables
Detemine how well/badly does it work and which variable is the most important one

### Task 4
Try to build a better prediction model that works somewhat harder to solve the task. Perhaps it will preprocess features better (e.g. normalize or scale the input vector, convert non-numerical value into float, or do a special treatment of missing values). Perhaps it will use a different machine learning approach (e.g. nearest neighbors, random forests, etc). Which of your models minimizes the squared error?

### Task 5
Predict all the logerror for instances at file “sample_submission.csv”. a) Write the result into a csv file and submit it to the website. b) Report the score you get

### Task 6
Write a 2-3 page report about your favorite model. The report should include:
- A description of how it works
- An evaluation of how well it works
- Any interesting experiences or surprises you had over the course of these experiments

## PART 2: Data Integration and Modeling
### Task 1
- Build a scoring function to rank houses by “desirability”, presumably a notion related to cost or value.
- Identify what the ten most desirable and least desirable houses in the Kaggle data set are.
- Describe which variables your function used and how well you think it worked

### Task 2
- Define a house “pairwise distance function”, which measures the similarity of two properties. Like a distance metric, similar pairs of very similar properties should be distance near zero, with distance increasing as the properties grow more dissimilar
- Experiment with your distance function, and write a one page discussion evaluating how well you think it worked. Your function should include geographic as well as property-specific variables

### Task 3
- Using your distance function and an appropriate clustering algorithm, cluster the houses using your distance function into 10 to 100 classes, as you see best.
- Present a dot-plot/map (with tiny dots colored to reflect the clustering) illustrating the clusters your method produced.
- Discuss/analyze of what your clusters seem to be capturing, and how well they work

### Task 4
- Identify at least one external data set which you can integrate into your price prediction analysis to make it better. Perhaps it can be financial, such as the historical effects of interest rates, consumer confidence, etc. on housing prices. Perhaps it can be geographic, like the crime rate, educational scores, income levels, etc.
- Discuss on whether this data helps with the prediction tasks

### Task 5
- Finally, build the best prediction model you can to solve the Zillow task. Use any data, ideas, and approach that you like. Predict the logerror for instances at file “sample_submission.csv”
- Report the score/rank you get
- Write a 2-3 page report about how it works, an evaluation, and any interesting experiences along the way

### Task 6
- Do a permutation test to determine a p-value of how good your predictions of logerror are. You can use whatever metric you wish to score your model (like mean absolute error)
- For a large enough sample of the evaluation data, compare how your model ranks by this metric on the real data compared to 100 (or more) random permutations of the logerror assigned to the real data records
- What fraction of permutations produce at least error at least as good at the real data set? If necessary, sample your data so these 100+ runs do not take too much time

### Task 7
Submit your results on the real test data to Kaggle before deadline. Write the result into a csv file and submit it to the website. Actually, submit two for your two best models, to the extent that Zillow allows it


