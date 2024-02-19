## Data Cleaning

our dataset consists of five separated datasets which are:

1. ##### Out_of_school_rates
2. ##### Attendance_rate
3. ##### Completion_rate
4. ##### information_communication_technological skills
5. ##### literacy_rate

each of the above dataset contains empty cells, abnormally and our of range data values.
in order to make the dataset analysis ready, as each of the data points are consist of countries and their attributes, the data points divided into four regions:

1. Least Developed
2. Less Developed
3. More Developed
4. Not Classified

From each of the above categories, we took the median for each specific variables and filled the missing values of those variables with their respective variables and categories.
For instance, based on the data Afghanistan is in the least developed countries, if there is any missing value for any of the columns related to Afghanistan. That missing part is filled only with the median of least developed countries, not with more developed countries.

The same procedure had been applied to all of the above mentioned dataset.

For you reference, you can use <a href="./literacy_rate.ipynb">literacy rate notebook</a> for cleaning the raw data and look through deeply into the dataset.
