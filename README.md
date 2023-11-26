# Exploratory-Data-Analysis
Exploratory Data Analysis (EDA) is a crucial step in understanding your dataset's characteristics, uncovering patterns, and identifying relationships between variables. Here's a step-by-step guide on conducting EDA using Python and Jupyter Notebook.
1. Load Necessary Libraries and Data
   This code snippet will read the CSV file into a Pandas DataFrame named df. Adjust the file name ('your_dataset.csv') and path to match the location of your dataset.
   If your dataset is in a different format or location (like Excel, JSON, SQL database, etc.), Pandas provides similar functions (read_excel, read_json, read_sql, etc.) to load data from 
   various sources.
2. Initial Data Exploration
   df.info() provides information about the columns, their data types, and non-null values.
   df. describe() gives a statistical summary (mean, standard deviation, min, max, etc.) of numerical columns.
   df. isnull().sum() counts missing values in each column.
   df. head() will display the first few rows of your dataset, giving you an idea of its structure and content Etc
3. Categorical Variable Analysis
   These visualizations help in understanding the distribution of categorical variables, identifying dominant categories,
    and exploring relationships between different categorical columns within your dataset.
    Adjust column names and plots based on your specific dataset's column names and analysis requirements.
5. Missing Values and Outliers and filling
   These methods help in dealing with missing values by filling them appropriately and addressing outliers to
   ensure they don’t unduly influence your analysis. Choose the method that best suits your data and analysis objectives.
7. Finding the answer to the given questions.
   Answering the given questions by detailed analysis of data and if need any alteration of datatype or values, it performed.
9. Bivariate Analysis by plotting the answers.
    This plot displays pairwise relationships among multiple numerical variables.
    These visualizations aid in understanding relationships between different variables in your dataset. 
    Adjust column names and plot parameters based on your dataset's structure and analysis requirements.


## Question for EDA
   Providing a dataset of employees working in ABC company. It consists of 458 rows and 9 columns. The company needs a detailed report and explanation of their employees in each team, also need to identify the following:
1.How many are there in each Team and the percentage splitting with respect to the total employees.
2.Segregate the employees w.r.t different positions.
3.Find from which age group most of the employees belong to.
4.Find out under which team and position, spending in terms of salary is high.
5.Find if there is any correlation between age and salary , represent it visually.
Before doing the above questions, perform pre processing of the dataset. Also, the column height is having incorrect data, changing the data of that particular column with any random numbers between 150 and 180.

