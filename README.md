# Machine and Deep Learning Solutions for Bank Direct Marketing Campaigns
The code was split into two parts
<br>
## Part 1: 
### 1. Loading the Dataset Under Study
### 2. Data Understanding
#### &ensp; 2.1 Checking the Dimension of the dataset under study
#### &ensp; 2.2 Checking the data types of the attributes in the data set under study
#### &ensp; 2.3 Checking the Descriptive Statistics of all quantitative attributes in the data set under study
#### &ensp; 2.4 Checking the Descriptive Statistics of all qualitative attributes in the data set under study 
#### &ensp; 2.5 Checking the Class Distribution
#### &ensp; 2.6 Checking if we have duplicated rows / records
#### &ensp; 2.7 Checking if we have missing and NULL Values
#### &ensp; 2.8 Checking if we have duplicated rows

### 3. Data Visualization
#### &ensp; 3.1 Univariate Visualization
##### &ensp;&ensp;&ensp;&ensp; 3.1.1 Histograms of the quantitative attributes in data set under study
##### &ensp;&ensp;&ensp;&ensp; 3.1.2 Box plots of the quantitative attributes in the data set under study
##### &ensp;&ensp;&ensp;&ensp; 3.1.3 Bar charts of qualitative attributes in the data set under study

#### &ensp; 3.2 Multivariate Visualization
##### &ensp;&ensp;&ensp;&ensp; 3.2.1 Histograms by class value of quantitative attributes
##### &ensp;&ensp;&ensp;&ensp; 3.2.2 Bar charts by class value of qualitative attributes in the data set under study

### 4. Data Pre-processing
#### &ensp; 4.1 Outlier Detection and Filtering & Dropping Duplicate Rows
#### &ensp; 4.2 Variable Preprocessing
##### &ensp;&ensp;&ensp;&ensp; 4.2.1 Label-Encoding for Output Variable
##### &ensp;&ensp;&ensp;&ensp; 4.2.2 One-Hot Encoding for categorical features, except for education which is an ordered variable
###### &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp; 4.2.2.1 Ordinal Encoding for categorical ordered feature
###### &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp; 4.2.2.2 One-Hot Encoding for the categorical features with no ordinal relationship
##### &ensp;&ensp;&ensp;&ensp; 4.2.3 Note on processing the numerical Variable pdays
#### &ensp; 4.3 Data Normalization
#### &ensp; 4.4 Feature / Variable Selection
##### &ensp;&ensp;&ensp;&ensp; 4.4.1 Correlation Map between Variables
##### &ensp;&ensp;&ensp;&ensp; 4.4.1 MultiCollinearity Checking


## Part 2: 
#### &ensp; 4.5 Dataset Balancing using Synthetic Minority Oversampling (SMOTE) Technique 
### 5. Building and Tunning the Classifiers
#### &ensp; 5.1 Conventional Methods
##### &ensp;&ensp;&ensp;&ensp; 5.1.1 Model 1-1 : Logistic Regression
##### &ensp;&ensp;&ensp;&ensp; 5.1.2 Model 1-2 : Decision Tree
#### &ensp; 5.2 Ensemble Methods
##### &ensp;&ensp;&ensp;&ensp; 5.1.1 Model 2-1 : Randome Forest
##### &ensp;&ensp;&ensp;&ensp; 5.1.2 Model 2-2 : XGBoost 
#### &ensp; 5.3 Multilayer Perceptron Neural Networks - MLP
##### &ensp;&ensp;&ensp;&ensp; 5.3.1 Model 3-1 : MLP with one hidden layer - MLP1
##### &ensp;&ensp;&ensp;&ensp; 5.3.2 Model 3-2 : MLP with Three hidden layers - MLP3 
##### &ensp;&ensp;&ensp;&ensp; 5.3.3 Model 3-3 : MLP with Five hidden layers - MLP5
#### &ensp; 5.4 Deep Learning - LSTM & CNN
##### &ensp;&ensp;&ensp;&ensp; 5.4.1 Model 4-1 : LSTM - with one LSTM
##### &ensp;&ensp;&ensp;&ensp; 5.4.2 Model 4-2 : CNN1 + LSTM2

### 6. Model Comparison
#### &ensp; 6.1 Comparing the MODELs regarding AUC
#### &ensp; 6.2 Comparing  the Models regarding Brier Score
#### &ensp; 6.3 Comparing the Models regarding Partial Gini
#### &ensp; 6.4 Comparing the Models regarding the Average Performances
