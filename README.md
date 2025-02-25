# Vikas Dhakad
# Adult income analysis using pandas 
**detailed description of this project**
1. **Display Top 10 Rows of The Dataset**
   - Used `data.head(10)` to display the first 10 entries of the dataset, showcasing various attributes like age, workclass, education, and income.

2. **Check Last 10 Rows of The Dataset**
   - Utilized `data.tail(10)` to view the last 10 entries, confirming the structure and values of the dataset.

3. **Find Shape of Our Dataset**
   - Executed `data.shape` to determine the dimensions of the dataset, which has 48,842 rows and 15 columns.

4. **Getting Information About Our Dataset**
   - Used `data.info()` to gather details about the dataset, including the number of non-null entries, data types, and memory usage.

5. **Fetch Random Samples from Dataset**
   - Retrieved a random sample of 50% of the dataset using `data.sample(frac=0.5)` to analyze a subset of the data.

6. **Check Null Values In The Dataset**
   - Checked for null values using `data.isnull().sum()` and visualized the results with a heatmap to identify missing data.

7. **Perform Data Cleaning (Replace '?' with NaN)**
   - Identified and replaced '?' values in specific columns with NaN to facilitate better data handling.

8. **Drop All the Missing Values**
   - Calculated the percentage of missing values and dropped rows with any missing data, resulting in a dataset of 45,222 rows.

9. **Check For Duplicate Data and Drop Them**
   - Checked for duplicates using `data.duplicated().any()` and removed any duplicate entries from the dataset.

10. **Get Overall Statistics About The Dataframe**
    - Used `data.describe()` to obtain statistical summaries of numerical columns, including count, mean, and standard deviation.

11. **Drop The Columns education-num, capital-gain and capital-loss**
    - Removed specified columns from the dataset to simplify the analysis.

12. **What Is The Distribution of Age Column?**
    - Analyzed the distribution of the age column using `data.age.describe()` and visualized it with a histogram.

13. **Find Total Number of Persons Having Age Between 17 to 48**
    - Counted the number of individuals aged between 17 and 48 using conditional filtering.

14. **What is The Distribution of Workclass Column?**
    - Analyzed the distribution of the workclass column and visualized it with a histogram.

15. **How Many Persons Have Bachelors or Masters Degree?**
    - Counted the number of individuals with either a Bachelors or Masters degree using conditional filtering.

16. **Bivariate Analysis**
    - Conducted a bivariate analysis using a boxplot to compare age distribution across income categories.

17. **Replace Income Values ['<=50k','>=50k'] with 0 and 1**
    - Created a function to convert income categories into binary values (0 for <=50K and 1 for >50K).

18. **Which Workclass is Getting the Highest Income?**
    - Grouped the dataset by workclass and summed the income to identify which workclass has the highest total income.

19. **Who Has Better Chance To Get Salary >50K, Male or Female?**
    - Analyzed the average income by gender to determine which gender has a better chance of earning more than 50K.

20. **Convert Workclass Column's Datatype to Category Datatype**
    - Changed the datatype of the workclass column to 'category' for more efficient memory usage and analysis. 
## Thank you for showing intrest in my project ##
