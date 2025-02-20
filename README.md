# FDA Food Event: Soft Drink/Water 

## Quick Start

1. **Clone the Repository:**
```

   git clone https://github.com/ruangkawprc/AppliedDataScience_Project1.git
```
2. **Run the Analysis Script:**

   Navigate to the project directory and run the script to start the analysis:
```

   python fda_food_data_analysis.py
```
3. **Alternatively, Use Jupyter Notebook:**

   If you prefer to use a Jupyter Notebook for analysis, open the notebook file and run the cells: fda_food_data_analysis.ipynb


## Introduction

As one of the most commonly consumed products, soft drinks/water products have far-reaching effects beyond simple weight gain. In severe cases, consumption can lead to hospitalization, disability, or even life-threatening consequences. To better understand these risks, we leverage the openFDA Food, Dietary Supplements, and Cosmetic Adverse Event API, which provides data from the Center for Food Safety and Applied Nutrition's Adverse Event Reporting System (CAERS). This database contains information on adverse event and product complaint reports submitted to the FDA from 2004 to 2025-02-16.

Our goal is to explore various product types within the soft drink and water industry, identify vulnerable groups (such as age and gender), and analyze the reactions, severity of impact, and correlation of symptoms associated with these products.

## Datasets

1. **Raw Dataset:** data/raw_fda_soft_drink_data.json
2. **Cleaned Dataset:** data/cleaned_fda_soft_drink_data.csv
3. **Processed Dataset:** data/processed_fda_soft_drink_data.csv

## Each member’s contribution


*   **Preach Apintanapong:** Preach is responsible for finding the data source from FDA, acquiring it using API requests, and performing data cleaning processes, as well as handling the GitHub repository.
*   **Liu Yang:** Liu is responsible for conducting exploratory data analysis (EDA), creating visualizations using tools like Matplotlib and Seaborn, identifying trends and anomalies in the data, and summarizing key insights to guide further analysis.
*   **Jingxi Li:** Jingxi is responsible for conducting exploratory data analysis, exploring the data by distribution and covariance analysis, as well as helping to optimize the API acquiring process.
*   **Yemin Wang:** Yemin is responsible for data preprocessing and feature engineering, including encoding catagorical variables and creating new features

