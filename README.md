# Coursework

- Included within this repository is a collection of assignments and projects which demonstrate learned tools and skills for programming and data analysis. 

## Data Analytics 
#### Professor Alex Pang - Queens College, City University of New York
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
    - Used seaborn library to create pairplot in order to assess relationship between attributes using scatterplots and histograms
    - Used pandas library with correlation function to check which attributes have the strongest affect on housing prices
    - Used sklearn library in order to generate a linear regression model fit with values from attributes sharing the highest correlation (*Income* and *Price*)
    - Used matplotlib pyplot library in order to plot predicted values of linear regression as a red line against scatterplot of actual data values
    - Used sklearn library with train_test_split function in order to train a new linear regression model, and test its ability to make predicitons on 20% of the training data from the previous attributes.
    - Used k-fold cross validation in order to test skill of the models.
  - **Used pandas library to load data from *affairs2.csv* dataset into dataframe**
    - Applied function call to convert numbers with decimal values into integers (1 or 0) within attribute in order to create target value
    - Used seaborn library in order to generate heatmap of data to check for rows with missing values, and generate factor plots to compare the significance of attributes
    - Used sklearn library with train_test_split function in order to train a logistic regression model using select attributes from dataset
    - Used pandas library with one-hot encoding/get_dummies function in order to convert categorical data ('Occupation') into numerical data and include in training set of logistic regression model
    - Used sklearn library with classification_report and accuracy_score functions in order to generate performance metrics of the prediction models.

- **DA_SVM_DecTrees_Affairs**
  - **Used pandas library in order to load data from *affair2.csv* dataset into dataframe**
    - Applied lambda function to convert numbers with decimal values into integers (1 or 0) within attribute in order to create target value
    - Used pandas library with one-hot encoding/get_dummies function in order to convert categorical data into numeric data
    - Used sklearn library with train_test_split and svm in order to train prediction models using Support Vector Classification (SVC), comparing optiimal choices of 'kernel', 'C', and 'gamma' parameters.
    - Used sklearn library with DecisionTreeClassifier in order to train prediction models using decision trees, comparing optimal choices for max_depth and criterion parameters. 
    - Used sklearn with export_graphviz in order to visualize decison trees.
    - Used sklearn with RandomForestClassifier in order to train prediction models using multiple decision trees.
  
- **DA_LogisticRegressionDecTree_LendingClubLoan**
  - **Used pandas library in order to load data from *lendingclub_loan_data.csv* dataset into dataframe**
    - Found and removed missing values from dataset
    - Used seaborn library with boxplots and scatter plots in order to remove outliers
    - Used pandas library with correlation function in order to assess which attributes have the strongest relationship
    - Used sklearn with StandardScaler and MinMaxScaler in order to normaliize data belonging to select attributes with negative values into a '0 - 1' scale
    - Used pandas library with one-hot encoding/get_dummies function in order to convert categorical data into numeric data
    - Used sklearn with LogisticRegression in order to train logistic regression models with and without categorical variables in order to assess improvement of performance metrics (precision, recall, F1-score, accuracy) as well as k-fold cross validation
    - Used sklearn library with DecisionTreeClassifier in order to train prediction models using decision trees, comparing optimal choices for max_depth and criterion parameters, as well as k-fold cross validation.
    - Used sklearn with export_graphviz in order to visualize decision trees. 


## Artificial Intelligence
##### Professor Liang Zhao - Lehman College, City University of New York
- **AI_LinearPolynomialRegression_Advertising**
  - **Used pandas library in order to load data from *advertising.csv* dataset into dataframe**
    - Used pandas library with histogram function in order to plot each attribute within the dataframe onto a histogram and visualize the data distribution.
    - Used seaborn library to create pairplot in order to assess relationship between attributes with scatter plots and histograms.
    - Used matplotlib library to create a scatterplot, in which the advertising budget belonging to TV, radio, and newspaper were plot against the generated sales.
    - Used sklearn library with train_test_split and LinearRegression functions in order to train a multilinear linear regression model using advertising budget of 3 input variables (TV, radio, newspaper) in order to make predictions on the sales generated, and compared the predicted values with the actual sales figures for each iteration of the test set.
    - Used sklearn library with PolynomialFeatures and mean_squared_error in order to train polynomial features models using different degree parameters (degree=2 and degree=10), and comparing the mean squared error (MSE)

- **AI_DecTreeRandomForest_Titanic**
  - **Used pandas library in order to load data from *titanic.csv* dataset into dataframe** 
    - Used sklearn library with train_test_split, DecisionTreeClassifier, and plot_tree functions in order to train and visualize prediction models using decision trees, comparing optimal choices for max_depth and identify possible contributing factors toward survival. 
     
- **AI_KerasCNN_FashionMNIST**
  - **Used tensorflow library in order to import fashion_mnist dataset**
    - Scaled the values of the train and test images by dividing each by 255.0
    - Used tensorflow library in order to build a convolutional neural netowrk model with three layers, the first which allows for flattening input of 2-dimensional arrray of 28x28 pixel images from training set into a 1-dimensional arrray, the second which is a dense layer of 128 nodes, and the third which allows for 10 units of output depending on the classification. The model was compiled using the adam optimizer, and fit using the training images, training labels, and evaluated using 10 epoch phases over the training set, displaying the accuracy with each iteration. 
    - Used matplotlib library in order to graph accurracy vs. epoch iterations on a line graph.
    - Used sklearn library in order to print a confusion matrix in order to demonstrate accuracy of model predictions across the 10 classes.

- **AI_Classification_TelcoChurn**
  - **Used pandas library in order to load data from *WA_Fn-UseC_-Telco-Customer-Churn.csv* dataset into dataframe** 
    -  

## Physics for Computer Science
