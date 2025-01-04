# data-mining-project-with-decision-tree-method-in-Orange-application 
# BLM0463 Introduction to Data Mining

## Summary
In this project, using Orange platform and Maternal Health Risk dataset, classification was performed with decision tree based methods and results were obtained. The dataset is taken from [UCI Machine Learning Repository](https://archive.ics.uci.edu/).

## Objective
The aim of the project is to perform classification on the dataset using the selected method, evaluate and present the results. In addition, a previous academic study on this dataset was found and the results were compared.

## Data Set and Preprocessing

#### Data Set
The dataset used is the Maternal Health Risk dataset. This data set includes:
- Age, Systolic Blood Pressure (Systolic BP), Diastolic Blood Pressure (Diastolic BP), BS (respiratory rate) and heart rate.
- The last attribute indicates the label of the data and includes three classes: High Risk, Medium Risk, Low Risk.
- The dataset consists of 6 features and 1013 samples.
- There are no missing values in the data set.

#### Preprocessing
Data preprocessing steps were performed on the data set before classification:
- Data Standardization was performed and all data were brought to the same scale.
- Data are sorted in tabular order.

## Classification Method
In this project, Decision Tree based Methods were used. Decision trees classify data by dividing them into branches according to their characteristics. This method was preferred in previous studies where the dataset was used because it yielded more accurate results compared to other methods.

## Training and Evaluation of the Model

### Model Training
- The decision tree model was trained using the training data set.
- The hyper-parameters of the model were optimized.
- All features are included in the model and no features are excluded.

### Model Evaluation
- The model was evaluated on the test data set.
- As evaluation criteria:
  - Accuracy
  - Sensitivity
  - Specificity
  - F-measure was used.
- These metrics were calculated using the "Test and Score" module of the Orange platform.
- Model performance has been improved by adding cross-validation.

## Separation of Training and Test Sets
- The data set is divided into training and test set:
  - Training set: Used for learning the model (70%).
  - Test set: It was used to assess the accuracy of the model (30%).

## Results and Comparison
The results of the project are evaluated and compared with an existing academic study. This provides a more comprehensive analysis of the success of the method and its application.

---

## Resources
- Dataset: [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- Orange Platform: [Orange](https://orangedatamining.com/)

## Developer Notes
This project was developed to test the performance of decision trees on real data sets and to evaluate the results in an academic context. For more information and suggestions, please contact me!
