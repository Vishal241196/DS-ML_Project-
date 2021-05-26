# How To Work On Any Project :- 
 1. Data Collection or Load the Data
 2. Problem :
    -> Identify the Bussiness Case and Categorize the Type of Problem to Solve 
       i.e. Regression, Classification, Time Series etc.
 3. Exploratory Data Analysis 
    * Identify the Independent and Dependent Variable
    * Statistical Analysis 
    * Data Visualization(Graphical Analysis):
      * Check Correlation Matrix with Heatmap :
        - Correlation states how the features are related to each other or the target variable.
        - Correlation can be positive (increase in one value of feature increases the value of the target variable) or
          negative (increase in one value of feature decreases the value of the target variable)
        - Heatmap makes it easy to identify which features are most related to the target variable
      * Univariate, Bivariate, Multivariate Analysis :
        - Histogram, line, Bar, Pie Chart, Scatter and other etc. Plot
        - Pairwise Correlation plots of all the relevant and majorly significant features
 4. Data Preprocessing :
    * Data Reduction :
      - Remove Unwanted Columns like ID, Columns which Most of Values is Missing
    * Data Cleaning :
      - Impute Missing Values
      - Categorical Variable Encoding
      - Replacing NaN Values
      - Check for Outliers :
         + Convert Categorical Data into Numerical using Label Encoding, One Hot Encoding, Binary Encoding etc.
    * Data Intregation : 
      - Merge the data from multiple source 
    * Feture Enng. : 
      - Feature Selection : 
        - Check Correlation Matrix :
           * Pearson Correlation
           * Extra Tree Classifier
           * Heatmap etc.
        - Feature importance
        - removing less correlated features 
      - Feature Scaling : 
        - Check Distribution
        - Format the Data (Normalization and Standadization)
      - Handle Imbalance Data if Data isn't Balanced
 5. Model Selection and Building :
    * Defining X and y
    * Splitting the Data
    * Select Model Which is Shoutable for our Project
 6. Creating and Training the Model
    * Hyperparameter Tuning :
      - GridSearchCV
      - RandomizedSearchCV
    * Fitting the Model
    * PCA
 7. Model Evaluation :
    * For Classification Problem :
         - Confusion Matrix
         - Accuracy Score
         - Error Rate
         - Precision Score
         - Recall Score
         - F1 Score
         - Specificity
         - Precision-Recall Curve(PR Curve)
         - Receiver Operating Character Curve(ROC Curve)
         - PR vs ROC Curve
         - ROC AUC Curve
    * For Regression Problem :
        - R2 Score
        - adj. R2 Score
        - Root Mean Squre Error (RMSE)
        - Log Loss
    * Save and Load the model  
 
8. API
    * Creating API File
    * Creating Web Page
    * Load Project on Cloud

### How To Identifing any Problem

S.N.    Problem          No. of Target        Target Cordinality         Type of Target
  1.    Binary Class           
        Classification         1                    =2                     Multi Class

  2.    Multi Class           
        Classification         1                    >2                     Multi Class
  
  3.    Multi Label   
        Classification        >1                    2(0 or 1)              Multi Label
        
  4.    Multi Output                                                       Continuous
        Regression            >1                    Continuous             Multi Output 
  
  5.    Multi Output                                                       
        Multi Class           >1                    >2                     Multi Class
        Classification                                                     Multi Output
        
Categorical Data = (0, 1), (0, 1, 2, 3), (A, B), (java, python, ml)
 Countinous Data = 10,40,10.5, 1-4,25-50
 
----------------------------------------------------------------------------------------------------

                    |          Un-Supervised                    |          Supervised
                    | 1. Clustering & Dimensionally Reduction   | 1. Regression
                    |    -> SVD                                 |    -> Linear                                 
                    |    -> PCA                                 |    -> Polynomial
      Continuous    |    -> K-Means                             | 2. Neural Network
                    |                                           | 3. Decision Tree
                    |                                           | 4. Random Forest
                    
----------------------------------------------------------------------------------------------------- 

                    | 1. Association Analysis                   | 1. Classification
                    |    -> Apriori                             |    -> KNN 
                    |    -> F-D Growth                          |    -> SVM
      Categorical   | 2. Hidden Markov Model                    |    -> Trees
                    |                                           |    -> Logistic Regression
                    |                                           |    -> Naive Bayes
                    |                                           |    -> Naive Bayes
                    
------------------------------------------------------------------------------------------------------

S.N.   Algorithms            Type                        Used For Problem
  1.   Linear Regression     Supervised, Countinuous     Regression
  2.   Logistic Regression   Supervised, Categorical     Classification
  3.   K-Mean                Un-Supervised, Continuous   Clustering & Dimentionality Reduction
  4.   KNN                   Supervised, Categorical     Classification
  5.   Decision Tree         Supervised, Both            Classification
  6.   Random Forest         Supervised, Countinuous     Both Classification, Regression
  7.   SVM                   Supervised, Categorical     Both Classification, Regression
  8.   Naive Bayes           Supervised, Categorical     Classification
  9.   XGBoosT               Supervised                  Classification, Regression, others
 10.   ANN                   Supervised                  Classification, Clustering, others 
 11.   PCA                   Un-Supervised, Continuous   Clustering & Dimentionality Reduction 