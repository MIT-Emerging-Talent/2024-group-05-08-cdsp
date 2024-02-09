---
name: help-wanted
about: A template issue for when you're blocked on certain lines of code.  This
  template has a lot of sections to get you thinking about your question, you
  don't need to fill in every one of them
title: "Help: (describe what is blocking you)"
labels: help-wanted
---

<!--
  Make your issue easy to find:

  - milestone: the challenge type
  - labels: anything that will make this easier to filter
  - assign: anyone you would like help from
-->

## The Code 

After exploring throughly the literacy dataset from the UNICEF. I found out that there are countries that don't have any value to perform stratified imputation. There are 6 countries which do not have any literacy related data. In addition, their economic statuses are labeled as 'not classified'. When I performed the stratified imputation based on the economic status of countries, these 6 countries outstanded as a separate group. The problem is there is no data to impute. For now, I added them back to the dataset along with other imputed strata. 

![Unclassified_Countries](https://drive.google.com/file/d/1ZHJldzhz6g4P8yTx_2DR3ecP9Qm0xnC0/view?usp=drive_link)

<!--
  The code you have a question about (it doesn't need to be your code!). This can
  be shared a few ways:

  - a snippet in the MD of your issue or
  - a permalink: https://help.github.com/en/github/managing-your-work-on-github/creating-a-permanent-link-to-a-code-snippet
    or
  - a gist: https://help.github.com/en/github/writing-on-github/creating-gists
-->

## Best Understanding

### Imputation 

In order to impute the missing values, we need to identify how many missing values are there and whether are they missing at random. The problem is there are rows where all the data are missing as a whole. In addition, the data are not missing at random, and removing them from the dataset completely will certainly introduce certain biases. 

On the other hand, imputing directly as a column will introduce outliers because the dataset contains developed countries that have high literacy rates and least developed countries which have low literacy rates. If we substitute the mean/median that is calculated based on these variables for the missing values will certainly introduce biases to the dataset. 

Therefore, I will divide the countries into different groups based on their economic status <b>('Development Regions' in the dataset)</b>. This process can reduce the number of biases because the imputation of mean or median would take in each group. For example, a certain developed country variable which can become the outlier will not affect other groups. This process of dividing the dataset into different groups based on certain characteristics and performing imputation is called <b>"Stratified Imputation"</b>.

##### Definition: Stratified imputation involves dividing the data into strata (e.g., by region, income group, or development status) and imputing missing values within each stratum separately. This approach helps account for differences in literacy rates across different groups and reduces bias.

<!--
  Explain the situation:

  - What _does_ the code do
  - What do you _want_ it to do
  - How do you think it works?
  - What don't you understand about how it works?
-->

## Best Efforts

<!--
  If this is your code and it has a bug, explain what you've tried so far:

  - Include code
  - Mention everything you tried, even if it seems silly to you
  - What happened with each effort?
  - What brought you closer?
  - What brought you farther?
-->

Among the different imputation methods, I would like to choose the median value to impute the null values a.k.a "NAN". Replacing null values with the mean or median of a certain column is very popular in imputation. "The technique, in this instance, replaces the null values with mean, rounded mean, or median values determined for that feature across the whole dataset (in our case, in each group). It is advised to utilize the median rather than the mean when your dataset has a significant number of outliers (Simplilearn, 2023)." For the 6 countries that I could not do any imputation methods, I added them back to the dataset as their original null values.

<b>Ref:</b> https://www.simplilearn.com/data-imputation-article

## Helpful Links

<!--
  Videos, articles, snippets, ... anything that helped you understand or make
  progress on the problem.
-->

To explore my data imputation process, here are the links to the source code file and data set. 

source code:https://drive.google.com/file/d/1vLAsedD_2AuR43fOCoakY8BBDavDe_D5/view?usp=sharing
data set:https://drive.google.com/file/d/1hWL59qGq6qwtzzh60nigYC0hknB8H2oU/view?usp=sharing 




## Hopeful Links

<!--
  Links that look like they should be helpful but you just can't put all the
  pieces together.
-->

For those who want to know about other imputation methods. Here is the link.

https://www.simplilearn.com/data-imputation-article