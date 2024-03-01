## Data Cleaning Process:

#### 1. Dataset Overview:

The dataset consists of five separate datasets:

- Out of school rates
- Attendance rate
- Completion rate
- Literacy rate
- GDP Expenditures on education

#### 2. Data Regions:

The data points are divided into four regions:

- Least Developed
- Less Developed
- More Developed
- Not Classified

#### 3. Handling Missing and Abnormal Data:

Identifying Missing Values:

Checked each dataset for empty cells and abnormal/out-of-range data values.

###### Region-Specific Medians:

Calculated medians for each variable within the four regions separately.

- Least Developed
- Less Developed
- More Developed
- Not Classified

##### Filling Missing Values:

Filled missing values of each variable with the median of its respective region.
If a data point belongs to the "Least Developed" region, missing values for that data point are filled with the median of "Least Developed" countries' values for that variable.
Similar procedure followed for "Less Developed" and "More Developed" regions.

#### 4. Example:

##### Scenario:

If a data point belongs to Afghanistan (classified under "Least Developed" region) and has missing values:
Missing values for each variable are filled with the median values of variables within the "Least Developed" countries.

#### 5. Standardized Cleaning Procedure

Apply to All Datasets:
The same cleaning procedure is applied to all five datasets: Out of school rates, Attendance rate, Completion rate, ICT skills, and Literacy rate.

#### 6. Ensuring Data Consistency and Quality

Validation:
After filling missing values, conducted validation checks to ensure data consistency and quality.
Verified that each data point now contains region-specific median values where missing values existed.

#### 7. Final Dataset

The cleaned dataset is now analysis-ready, with missing values replaced with region-specific medians.

#### 8. Literacy Rate Notebook

Refer to the provided <a href="../cleaning_progress/Literacy_Rate_Cleaning.ipynb">Literacy Rate Notebook</a> and <a href="../cleaning_progress/Completion_Rate.ipynb">Completion Rate Notebook</a> for a detailed look into the data cleaning process.
This standardized data cleaning procedure ensures that the dataset is compelling, standard, and ready for analysis, maintaining the integrity of region-specific data while preparing it for meaningful insights.
