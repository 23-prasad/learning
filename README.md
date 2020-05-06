# Data Science Assignment
1.Select three review categories of your choice. Scrape all reviews for each
category and store them as three separate datasets. For each review, you
should store the review text and a class label (i.e. whether the review is
“positive” or “negative”).
2. For each of the three category datasets:
  a. From the reviews in this category, apply appropriate preprocessing steps to
  create a numeric representation of the data, suitable for classification.
  b. Build a classification model to distinguish between “positive” and “negative”
  reviews using one of the following classifiers:
  Naive Bayes, Logistic Regression, Random Forests
  c. Test the predictions of the classification model using an appropriate
  evaluation strategy. Report and discuss the evaluation results in your
  notebook.
3. Evaluate the performance of each of your three classification models when
applied to data from the other two selected categories. That is, for the selected
categories (A,B,C), run the experiments:
  a. Train a classification model on the data from “Category A”. Evaluate its
  performance on data from “Category B” and data from “Category C”.
  b. Train a classification model on the data from “Category B”. Evaluate its
  performance on data from “Category A” and data from “Category C”.
  c. Train a classification model on the data from “Category C”. Evaluate its
  performance on data from “Category A” and data from “Category B”.
