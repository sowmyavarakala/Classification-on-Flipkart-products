# Classification-on-Flipkart-products

#### Classification of flipkart products using different machine learning algorithms.

##Dataset
I have used Flipkart-products dataset for classification of categories.

https://docs.google.com/spreadsheets/d/1pLv0fNE4WHokpJHUIs-FTVnmI9STgog05e658qEON0I/edit?usp=sharing

## Prerequisites :
Ideal to run the files in colab(I have attached the colab file links).

or

Softwares and libraries in the local machine before running this project.
* Anaconda : It will install an ipython notebook
* All the libraries in Requirements.txt

## Model and Results
Before diving into model classification, have a glance at the dataset.
Dataset have many columns which are unneccesary for model prediction.
* preprocessing.ipynb does all the cleaning and visualization of the dataframe.
* after all the preprocessing the final dataset with useful features is saves as flipkart_com-ecommerce_cleaned_sample.csv(uploaded in the repo).
* Classifier.ipynb takes in the cleaned dataset and predicts the categories using different models.

>**RandomForestClassifier**
* RandomForestClassifier gave an accuracy of around 88%.
*   average precision = 0.87
*  average recall = 0.87
*   average F1 score = 0.86
>**Naive Bayes classifier for multinomial models**
* Naive Bayes classifier for multinomial models gave an accuracy around 90%.
*   average precision = 0.89
*  average recall = 0.90
*   average F1 score = 0.89
>**DecisionTreeClassifier**
* DecisionTreeClassifier gave an accuracy of 93%.
*   average precision = 0.93
*  average recall = 0.93
*   average F1 score = 0.93

## References
* https://www.kaggle.com/learn/pandas
* https://scikit-learn.org/stable/modules/multiclass.html

## Done by 
sowmyavarakala




