# Data Wrangling Process

## Key Phrases:
1. **Data Loading**: Load the raw data into a Pandas dataframe.
2. **Handling Missing Values**: Identify and handle missing values in the dataset.
3. **Data Filtering**: Filter out irrelevant data, such as non-Falcon 9 launches.
4. **Data Transformation**: Convert categorical variables into numerical values using techniques like one-hot encoding.
5. **Feature Engineering**: Create new features or modify existing ones to improve the dataset's quality.
6. **Data Normalization**: Standardize the data to ensure all features contribute equally to the model.
7. **Data Storage**: Store the cleaned and processed data in a Pandas dataframe for further analysis.

## Flowchart

```plaintext
+-----------------------------+
|          Start              |
+-----------------------------+
              |
              v
+-----------------------------+
|        Load Data            |
|  (Pandas DataFrame)         |
+-----------------------------+
              |
              v
+-----------------------------+
|  Identify Missing Values    |
+-----------------------------+
              |
              v
+-----------------------------+
|  Handle Missing Values      |
|  (Fill or Drop)             |
+-----------------------------+
              |
              v
+-----------------------------+
|        Filter Data          |
|  (Remove Irrelevant Data)   |
+-----------------------------+
              |
              v
+-----------------------------+
|       Transform Data        |
|  (One-Hot Encoding)         |
+-----------------------------+
              |
              v
+-----------------------------+
|    Feature Engineering      |
|  (Create/Modify Features)   |
+-----------------------------+
              |
              v
+-----------------------------+
|      Normalize Data         |
|  (Standardization)          |
+-----------------------------+
              |
              v
+-----------------------------+
|        Store Data           |
|  (Pandas DataFrame)         |
+-----------------------------+
              |
              v
+-----------------------------+
|           End               |
+-----------------------------+
