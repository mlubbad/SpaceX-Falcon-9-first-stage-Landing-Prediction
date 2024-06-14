# SpaceX-Falcon-9-first-stage-Landing-Prediction
In this project, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch. In this module, you will be provided with an overview of the problem and the tools you need to complete the project.

## Learning Objectives ##
- Develop Python code to manipulate data in a Pandas data frame
- Convert a JSON file into a Create a Python Pandas data frame by converting a JSON file
- Create a Jupyter notebook and make it sharable using GitHub
- Utilize data science methodologies to define and formulate a real-world business problem
- Utilize your data analysis tools to load a dataset, clean it, and find interesting insights from it

## Lab 1: Collecting the data ##

### From API ###
In this lab [jupyter-labs-spacex-data-collection-api-2.ipynb](https://github.com/mlubbad/SpaceX-Falcon-9-first-stage-Landing-Prediction/blob/main/jupyter-labs-spacex-data-collection-api-2.ipynb), you will collect and make sure the data is in the correct format from an API.

### From Web Scrapping ###
In this lab [jupyter-labs-webscraping.ipynb](https://github.com/mlubbad/SpaceX-Falcon-9-first-stage-Landing-Prediction/blob/main/jupyter-labs-webscraping.ipynb), you will be performing web scraping to collect Falcon 9 historical launch records from a Wikipedia page titled [List of Falcon 9 and Falcon Heavy launches](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches)

## Lab 2: Data wrangling ## 
In this lab [labs-jupyter-spacex-Data%20wrangling.ipynb](https://github.com/mlubbad/SpaceX-Falcon-9-first-stage-Landing-Prediction/blob/main/labs-jupyter-spacex-Data%20wrangling.ipynb), we will perform some Exploratory Data Analysis (EDA) to find some patterns in the data and determine what would be the label for training supervised models.

### Hands-on Lab: Complete the EDA with SQL ### 
*Using this lab [jupyter-labs-eda-sql-coursera_sqllite-2.ipynb](https://github.com/mlubbad/SpaceX-Falcon-9-first-stage-Landing-Prediction/blob/main/jupyter-labs-eda-sql-coursera_sqllite-2.ipynb) you will:*
- Understand the Spacex DataSet
- Load the dataset into the corresponding table in a Db2 database
- Execute SQL queries to answer assignment questions

### Hands-on Lab: EDA with Visualization Lab ### 
*Assignment: Exploring and Preparing Data*

In this assignment, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is since SpaceX can reuse the first stage.

In this lab [edadataviz.ipynb](https://github.com/mlubbad/SpaceX-Falcon-9-first-stage-Landing-Prediction/blob/main/edadataviz.ipynb), you will perform Exploratory Data Analysis and Feature Engineering.

## Lab 3: Interactive Visual Analytics and Dashboard ##
In this module, you will build a dashboard to analyze launch records interactively with Plotly Dash. You will then build an interactive map to analyze the launch site proximity with Folium.

**Learning Objectives**
- Build an interactive dashboard that contains pie charts and scatter plots to analyze data with the Plotly Dash Python library.
- Calculate distances on an interactive map by writing Python code using the Folium library.
- Generate interactive maps, plot coordinates, and mark clusters by writing Python code using the Folium library.
- Build a dashboard to analyze launch records interactively with Plotly Dash.
- Build an interactive map to analyze the launch site's proximity with Folium.


## Lab 4: Predictive Analysis (Classification) ###
In this Lab, you will use machine learning to determine if the first stage of Falcon 9 will land successfully. You will split your data into training data and test data to find the best Hyperparameter for SVM, Classification Trees, and Logistic Regression. Then find the method that performs best using test data.
In this module, you will use machine learning to determine if the first stage of Falcon 9 will land successfully. You will split your data into training data and test data to find the best Hyperparameter for SVM, Classification Trees, and Logistic Regression. Then find the method that performs best using test data.

**Learning Objectives**
- Split the data into training testing data
- Train different classification models
- Optimize the Hyperparameter grid search
- Utilize your machine learning skills to build a predictive model to help a business function more efficiently

### Hands-on Lab: Complete the Machine Learning Prediction lab ###
In this Lab [SpaceX_Machine%20Learning%20Prediction_Part_5.ipynb](https://github.com/mlubbad/SpaceX-Falcon-9-first-stage-Landing-Prediction/blob/main/SpaceX_Machine%20Learning%20Prediction_Part_5.ipynb), we will review Predictive Analysis. In this lab, we will build a machine learning pipeline to predict if the first stage of the Falcon 9 lands successfully. This will include: Preprocessing, allowing us to standardize our data, and Train_test_split, allowing us to split our data into training and testing data, We will train the model and perform Grid Search, allowing us to find the hyperparameters that allow a given algorithm to perform best. Using the best hyperparameter values, we will determine the model with the best accuracy using the training data. You will test Logistic Regression, Support Vector machines, Decision Tree Classifier, and K-nearest neighbors. Finally, we will output the confusion matrix.
