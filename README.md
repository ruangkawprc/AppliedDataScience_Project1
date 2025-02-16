## data_cleaning.ipynb
**Data Acquisition**
- In this section, we utilize openFDA's Food API to explore adverse events related to FDA-regulated foods, dietary supplements, and cosmetics.
- Specifically, our focus is on the Soft Drink/Water industry.
- Due to API constraints, the maximum value for the limit parameter is currently set at 1000

**Data Cleaning and Handling Inconsistencies**
In this section, we will:

- Fix incorrect data formats (e.g., convert date from string to datetime).
- Correct the consumer and product columns, which contain data in nested dictionary format, by separating them into individual columns.
- Handle lists in the outcomes and reactions columns by creating dummy variables for each item in the list for further analysis.
- Remove missing values.
- Remove duplicate rows.
- Standardize all alphabets to lower case letters.
  
Lastly, we will show the summary of the unique values for each category.
