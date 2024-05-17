# Life-Expectancy-EDA-before-machine-learning
The project involved analyzing a dataset comprising approximately 3,000 rows and 20 columns, encompassing diverse variables.

## Exploratory Data Analysis (EDA)
During the exploratory data analysis phase, several critical steps were undertaken to ensure data integrity and prepare it for subsequent analysis. These steps included:

- **Null Value Handling**:  The dataset was thoroughly examined for missing values. Null values, where present, were identified and dealt with using appropriate strategies to maintain data completeness.
- **Checked for duplicates**
- **Outlier Detection and Treatment:** Robust techniques were employed to identify outliers in the dataset. After detection, outliers were carefully assessed and subsequently removed to prevent skewing of analytical results. For continuous data, outliers were adjusted by replacing them with the mean value between the upper and lower whiskers as depicted in box plots.

## Data Imputation
To address missing values effectively, the KNNImputer algorithm was utilized. This method leverages the k-nearest neighbors approach to impute missing values based on the similarity of neighboring data points.

## Feature Encoding
Categorical variables were encoded using dummy variables. However, to mitigate potential multicollinearity issues, the first level of each categorical variable was dropped. This approach ensures that the resulting encoded features remain independent and reduces redundancy in the dataset, thereby enhancing the robustness of subsequent analyses.
