# Coursework

- Included within this repository is a collection of assignments and projects which demonstrate learned tools and skills for programming and data analysis. 

## Data Analytics 
##### Professor Alex Pang - Queens College, City University of New York
- **DA_CarCrashes_MPG**
  - **Used pandas library in order to load data from *car_crashes2.csv* dataset into dataframe**
    - Checked for and removed null values
    - Used seaborn library in order to assess for outliers using scatterplots and boxplots
    - Used pandasql library in order to query and calculate statistics (mean, standard deviation, skew, kurtosis) from dataset using both SQL and pandas functions
    - Used seaborn library in order to check accident distribution by region by plotting histograms
    - Used correlation function to check which attributes have the strongest affect on causing accidents
  - **Used pandas library in order to load data from *mpg3.csv* dataset into dataframe**
    - Checked for missing values, imputed mean of attribute in place of missing values
  
- **DA_LinearLogisticRegression_HousingAffairs**
  - **Used pandas library to load data from *USA_housing.csv* dataset into dataframe**
    - Used seaborn library to create pairplot in order to assess relationship between attributes using scatterplots
    - Used correlation function to check which attributes have the strongest affect on housing prices
    - Used sklearn library in order to generate a linear regression model fit with values from attributes sharing the highest correlation (*Income* and *Price*)
    - Used matplotlib pyplot library in order to plot predicted values of linear regression as a red line against scatterplot of actual data values
    - Used sklearn library with train_test_split function in order to train a new linear regression model, and test its ability to make predicitons on 20% of the training data from the previous attributes.
    - Used k-fold cross validation in order to test skill of the models. 
  - **Used pandas library to load data from *affairs2.csv* dataset into dataframe**
    - Applied function call to convert numbers with decimal values into integers (1 or 0) within attribute in order to create target value
    - Used seaborn library in order to generate heatmap of data to check for rows with missing values, and generate factor plots to compare the significance of attributes
    - Used sklearn library with train_test_split function in order to train a linear regression model using select attributes from dataset
    - Used pandas library with one-hot encoding/get_dummies function in order to convert categorical data ('Occupation') into numerical data and include in training set of linear regression model
    - Used sklearn library with classification_report and accuracy_score functions in order to generate performance metrics of the prediction models.

- **DA_SVM_DecTrees_Affairs**
  - Used pandas library in order to load **affair2.csv** dataset into dataframe
    - Applied lambda function to convert numbers with decimal values into integers (1 or 0) within attribute in order to create target value
    - Used pandas library with one-hot encoding/get_dummies function in order to convert categorical data into numeric data
    - Used sklearn library with train_test_split and svm in order to train prediction models using Support Vector Classification (SVC), comparing optiimal choices of 'kernel', 'C', and 'gamma' parameters.
    - Used sklearn library with DecisionTreeClassifier in order to train prediction models using decision trees, comparing optimal choices for max_depth and criterion parameters. 
    - Used sklearn with export_graphviz in order to visualize decison trees.
    - Used sklearn with RandomForestClassifier in order to train prediction models using multiple decision trees.
  
## Artificial Intelligence
##### Professor Liang Zhao - Lehman College, City University of New York
-
## Physics for Computer Science
-
