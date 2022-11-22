# Machine and Deep Learning Solutions for Bank Direct Marketing Campaigns
The code was split into two parts
<br>
## Part 1: 
### 1. Loading the Dataset Under Study
### 2. Data Understanding: <h3> A general overview on the data set under study was provided in this step.</h3>
#### 2.1 Checking the Dimension of the dataset under study
#### 2.2 Checking the data types of the attributes in the data set under study
#### 2.3 Checking the Descriptive Statistics of all quantitative attributes in the data set under study
#### 2.4 Checking the Descriptive Statistics of all qualitative attributes in the data set under study 
#### 2.5 Checking the Class Distribution
#### 2.6 Checking if we have duplicated rows / records
#### 2.7 Checking if we have missing and NULL Values

### 3. Data Visualization: Different data visualization techniques was applied in this step, so we can expand our knowledge on the dataset.
#### 3.1 Univariate Visualization
##### 3.1.1 Histograms of the quantitative attributes in data set under study
##### 3.1.2 Box plots of the quantitative attributes in the data set under study
##### 3.1.3 Bar charts of qualitative attributes in the data set under study

#### 3.2 Multivariate Visualization
##### 3.2.1 Histograms by class value of quantitative attributes
##### 3.2.2 Bar charts by class value of qualitative attributes in the data set under study

### 4. Data Pre-processing
#### Duplicated rows and outliers that found in the dataset were removed in this step, so our data can be more consistent and accurate. Due to its robustness to outliers, the quartile and interquartile distance method was used in this study to detect and filter outliers from original columns <a href="https://www.sciencedirect.com/science/article/abs/pii/S235293852030639X">[Ref]</a>. Encoding was also applied in this step, so that ML and DL algorithms can easy understands the categorical features. Also, Data Normalization was applied in this step to prevent any bias may occur towards features with a higher magnitude. Additionally, highly correlated features were identified and removed in this step.
#### 4.1 Outlier Detection and Filtering & Dropping Duplicate Rows
#### 4.2 Variable Preprocessing: 
##### 4.2.1 Label-Encoding for Output Variable
##### 4.2.2 One-Hot Encoding for categorical features, except for education which is an ordered variable
###### 4.2.2.1 Ordinal Encoding for categorical ordered feature
###### 4.2.2.2 One-Hot Encoding for the categorical features with no ordinal relationship
##### 4.2.3 Note on processing the numerical Variable pdays
#### 4.3 Data Normalization: 
#### 4.4 Feature / Variable Selection: 
##### 4.4.1 Correlation Map between Variables
##### 4.4.1 MultiCollinearity Checking


## Part 2: 
#### 4.5 Dataset Balancing using Synthetic Minority Oversampling (SMOTE) Technique: <p> SMOTE technique was applied in this step to obtain a balanced dataset, and its was chosen due to its simplicity and effectiveness<a href="https://www.sciencedirect.com/science/article/pii/S1532046416301071">[Ref]</a>.</p> 
### 5. Building and Tunning the Classifiers
#### 5.1 Conventional Methods
##### 5.1.1 Model 1-1 : Logistic Regression
##### 5.1.2 Model 1-2 : Decision Tree
#### 5.2 Ensemble Methods
##### 5.1.1 Model 2-1 : Randome Forest
##### 5.1.2 Model 2-2 : XGBoost 
#### 5.3 Multilayer Perceptron Neural Networks - MLP
##### 5.3.1 Model 3-1 : MLP with one hidden layer - MLP1
##### 5.3.2 Model 3-2 : MLP with Three hidden layers - MLP3 
##### 5.3.3 Model 3-3 : MLP with Five hidden layers - MLP5
#### 5.4 Deep Learning - LSTM & CNN
##### 5.4.1 Model 4-1 : LSTM - with one LSTM
##### 5.4.2 Model 4-2 : CNN1 + LSTM2

### 6. Model comparison using statistical analysis 
#### 6.1 Comparing the Models using AUC
#### 6.2 Comparing  the Models using Brier Score
#### 6.3 Comparing the Models using Partial Gini
#### 6.4 Comparing the Models using the Average Performances
