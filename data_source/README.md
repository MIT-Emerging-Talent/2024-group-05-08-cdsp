Welcome to the data_source folder! Here, you'll find the backbone of our project, the raw_data section, centered on the UNICEF dataset covering various education levels. The cleaned_data section details our meticulous cleaning process, categorizing data by regions and utilizing medians for imputation. The cleaning_progress section offers ongoing insights into our data refinement journey. Below, you'll find our dataset glossary for further clarity.



### Project Data Overview:

Our project relies extensively on the <a href="https://data.unicef.org/topic/education/overview/" target="_blank">UNICEF</a> dataset, which covers a wide range of education levels, from pre-primary to youth and adult education. This dataset emphasizes measuring learning outcomes, skills acquisition, and ensuring equity in educational contexts, catering to both developmental and emergency settings.
We utilize insights from UNICEF's administrative records and household surveys to comprehensively assess children's school participation. By utilizing enrollment data and attendance information from diverse sources, we obtain a comprehensive view of primary and secondary education in developing countries. Notably, UNICEF's data align with the official International Standard Classifications of Education (ISCED), providing a standardized framework, albeit with potential variations compared to country-specific school systems.


### Key Indicators in UNICEF Education Dataset:

The UNICEF education dataset comprises various subsets, encompassing crucial indicators such as:
- Out of school rate
- Adjusted net attendance rate
- Completion rate
- Youth and adult literacy rate



### Possible flaws

<ul>
<li>The data was last updated on June 1, 2022, making it relatively outdated. Considering the dynamic nature of education and socio-economic factors, it's important to be mindful of the temporal gap when interpreting the findings. Continuous monitoring and potential updates to the dataset would enhance its relevance.</li>
<li>There are gaps in the completeness of the dataset, with certain countries having more pronounced missing values compared to others.</li>      
</ul>



### Datasets Glossary

- __ISO3:__ Three-digit alphabetical codes International Standard ISO 3166-1
- __Countries and areas:__ Countries and areas across the globe 
- __Region:__ UNICEF defined regions
- __Sub-region:__ UNICEF defined sub-regions
    - EAP	East Asia and the Pacific
    - ECA	Europe and Central Asia
    - EECA	Eastern Europe and Central Asia
    - ESA	Eastern and Southern Africa
    - LAC	Latin America and the Caribbean
    - MENA	Middle East and North Africa
    - NA	North America
    - SA	South Asia
    - SSA	Sub-Saharan Africa
    - WCA	West and Central Africa
- __Development Regions:__ Economies of the countries 
- __CR_Primary_Total:__ Primary level completion rate Total
- __CR_Primary_Female:__ Primary level completion rate Female
- __CR_Primary_Male:__ Primary level completion rate Male
- __CR_Primary_Residence_Rual:__ Primary level completion rate in Rural Area
- __CR_Primary_Residence_Urban:__ Primary level completion rate in Urban Area
- __CR_Primary_Wealth_Poorest:__ Primary level wealth quantile (poorest) 
- __CR_Primary_Wealth_Second:__ Primary level completion rate wealth quantile (second)
- __CR_Primary_Wealth_Middle:__ Primary level completion rate wealth quantile (middle)
- __CR_Primary_Wealth_Fourth:__ Primary level completion rate wealth quantile (fourth)
- __CR_Primary_Wealth_Richest:__ Primary level completion rate wealth quantile (richest)
- __CR_LowerSecondary_Total:__ Lower secondary level completion rate Total
- __CR_LowerSecondary_Female:__ Lower secondary level completion rate Female
- __CR_LowerSecondary_Male:__ Lower secondary level completion rate Male
- __CR_LowerSecondary_Residence_Rual:__ Lower secondary level completion rate in Rural Area
- __CR_LowerSecondary_Residence_Urban:__ Lower secondary level completion rate in Urban Area
- __CR_LowerSecondary_Wealth_Poorest:__ Lower secondary level completion rate wealth quantile (poorest) 
- __CR_LowerSecondary_Wealth_Second:__ Lower secondary level completion rate wealth quantile (second)
- __CR_LowerSecondary_Wealth_Middle:__ Lower secondary level completion rate wealth quantile (middle)
- __CR_LowerSecondary_Wealth_Fourth:__ Lower secondary level completion rate wealth quantile (fourth)
- __CR_LowerSecondary_Wealth_Richest:__ Lower secondary level completion rate wealth quantile (richest)
- __CR_UpperSecondary_Total:__ Upper secondary level completion rate Total
- __CR_UpperSecondary_Female:__ Upper secondary level completion rate Female
- __CR_UpperSecondary_Male:__ Upper secondary level completion rate Male
- __CR_UpperSecondary_Residence_Rual:__ Upper secondary level completion rate in Rural Area
- __CR_UpperSecondary_Residence_Urban:__ Upper secondary level completion rate in Urban Area
- __CR_UpperSecondary_Wealth_Poorest:__ Upper secondary level completion rate wealth quantile (poorest) 
- __CR_UpperSecondary_Wealth_Second:__ Upper secondary level completion rate wealth quantile (second)
- __CR_UpperSecondary_Wealth_Middle:__ Upper secondary level completion rate wealth quantile (middle)
- __CR_UpperSecondary_Wealth_Fourth:__ Upper secondary level completion rate wealth quantile (fourth)
- __CR_UpperSecondary_Wealth_Richest:__ Upper secondary level completion rate wealth quantile (richest)
- __ATR_Primary_Total:__ Primary level attendance rate Total
- __ATR_Primary_Female:__ Primary level attendance rate Female
- __ATR_Primary_Male:__ Primary level attendance rate Male
- __ATR_Primary_Residence_Rual:__ Primary level attendance rate in Rural Area
- __ATR_Primary_Residence_Urban:__ Primary level attendance rate in Urban Area
- __ATR_Primary_Wealth_Poorest:__ Primary level wealth quantile (poorest) 
- __ATR_Primary_Wealth_Second:__ Primary level attendance rate wealth quantile (second)
- __ATR_Primary_Wealth_Middle:__ Primary level attendance rate wealth quantile (middle)
- __ATR_Primary_Wealth_Fourth:__ Primary level attendance rate wealth quantile (fourth)
- __ATR_Primary_Wealth_Richest:__ Primary level attendance rate wealth quantile (richest)
- __ATR_LowerSecondary_Total:__ Lower secondary level attendance rate Total
- __ATR_LowerSecondary_Female:__ Lower secondary level attendance rate Female
- __ATR_LowerSecondary_Male:__ Lower secondary level attendance rate Male
- __ATR_LowerSecondary_Residence_Rual:__ Lower secondary level attendance rate in Rural Area
- __ATR_LowerSecondary_Residence_Urban:__ Lower secondary level attendance rate in Urban Area
- __ATR_LowerSecondary_Wealth_Poorest:__ Lower secondary level attendance rate wealth quantile (poorest) 
- __ATR_LowerSecondary_Wealth_Second:__ Lower secondary level attendance rate wealth quantile (second)
- __ATR_LowerSecondary_Wealth_Middle:__ Lower secondary level attendance rate wealth quantile (middle)
- __ATR_LowerSecondary_Wealth_Fourth:__ Lower secondary level attendance rate wealth quantile (fourth)
- __ATR_LowerSecondary_Wealth_Richest:__ Lower secondary level attendance rate wealth quantile (richest)
- __ATR_UpperSecondary_Total:__ Upper secondary level attendance rate Total
- __ATR_UpperSecondary_Female:__ Upper secondary level attendance rate Female
- __ATR_UpperSecondary_Male:__ Upper secondary level attendance rate Male
- __ATR_UpperSecondary_Residence_Rual:__ Upper secondary level attendance rate in Rural Area
- __ATR_UpperSecondary_Residence_Urban:__ Upper secondary level attendance rate in Urban Area
- __ATR_UpperSecondary_Wealth_Poorest:__ Upper secondary level attendance rate wealth quantile (poorest) 
- __ATR_UpperSecondary_Wealth_Second:__ Upper secondary level attendance rate wealth quantile (second)
- __ATR_UpperSecondary_Wealth_Middle:__ Upper secondary level attendance rate wealth quantile (middle)
- __ATR_UpperSecondary_Wealth_Fourth:__ Upper secondary level attendance rate wealth quantile (fourth)
- __ATR_UpperSecondary_Wealth_Richest:__ Upper secondary level attendance rate wealth quantile (richest)
- __OOR_Primary_Total:__ Primary level out of school rate Total
- __OOR_Primary_Female:__ Primary level out of school rate Female
- __OOR_Primary
