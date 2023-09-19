In this project I have been provided with a " Breast cancer" data set with contains the M or B starte in a person that is M = malignant or B = benign 
State of cancer in a person. 
It also contains the radius , area, texture, percentage etc... About the cancer . 
This data set contains of 33 column and 570 rows.
Applying ML to predict the presence of  cancer to the most accurate level possible is the task .

Steps taken to Process the data :

Analysis of the data : 
Since the data set is small  analysing and identifying the important column and removing the unwanted column is hard since it is small the details provided by this data set is very important value to the data set is important. But while analysing the dataset we can observe there is a empty column in the last and ID is not important after removing 
These colours we will end up with 31 column.

Data cleaning: 
 Before performing the cleaning we have to check whether this step is necessary by using 
" isnull .sum()" we can observe there is no null value in this data set. Which makes our task easier removing the duplicate value will be sufficient to train this data set.

Visualisation:
Evening though are main task is to train a module performing visualisation will help us gain valuable insights in the data set. Which will give us more advantage in modling part 

ML:
I have use random forest algorithm in ML to perform prediction . The following have been calculated to know the accuracy of this module 

Accuracy:
Accuracy is one metric for evaluating classification models. Informally, accuracy is the fraction of predictions our model got right. Formally, accuracy has the following definition: Accuracy = Number of correct predictions * Total number of predictions

PRECISION:
the quality of a positive prediction made by the model. Precision refers to the number of true positives divided by the total number of positive predictions.

RECALL:
Recall, also known as the true positive rate (TPR), is the percentage of data samples that a machine learning model correctly identifies as belonging to a class of interest

f1:
F1 score is a machine learning evaluation metric that measures a model's accuracy. It combines the precision and recall scores of a model. The accuracy metric computes how many times a model made a correct prediction across the entire dataset.

Conclusion:

model name is RandomForestClassifier()

Accuracy is 96.0% 
Precision is 93.0%
Recall is 98.8% 
f1 is 95.0 %



