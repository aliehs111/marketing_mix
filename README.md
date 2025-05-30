# Marketing Mix
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## Data description

The variables such as birth year, education, income, and others pertain to the first 'P' or 'People' in the tabular data presented to the user. The expenditures on items like wine, fruits, and gold, are associated with ‘Product’. Information relevant to sales channels, such as websites and stores, is connected to ‘Place’, and the fields discussing promotions and the outcomes of various campaigns are linked to ‘Promotion’.
Link to data: https://drive.google.com/file/d/1fl1QP7iNugNbiviueQp1WtoDBc-IezDD/view

## Steps to perform 

1. After importing the data, examine variables such as Dt\_Customer and Income to verify their accurate importation.  
2. There are missing income values for some customers. Conduct missing value imputation, considering that customers with similar education and marital status tend to have comparable yearly incomes, on average. It may be necessary to cleanse the data before proceeding. Specifically, scrutinize the categories of education and marital status for data cleaning.  
3. Create variables to represent the total number of children, age, and total spending.  
   * Derive the total purchases from the number of transactions across the three channels.  
4. Generate box plots and histograms to gain insights into the distributions and identify outliers. Implement outlier treatment as needed.  
5. Apply ordinal and one-hot encoding based on the various types of categorical variables.  
6. Generate a heatmap to illustrate the correlation between different pairs of variables.  
7. Test the following hypotheses:  
   * Older individuals may not possess the same level of technological proficiency and may, therefore, lean toward traditional in-store shopping preferences.  
   * Customers with children likely experience time constraints, making online shopping a more convenient option.  
   * Sales at physical stores may face the risk of cannibalization by alternative distribution channels.  
   * Does the United States significantly outperform the rest of the world in total purchase volumes?  
8. Use appropriate visualization to help analyze the following:  
   * Identify the top-performing products and those with the lowest revenue.  
   * Examine if there is a correlation between customers' age and the acceptance rate of the last campaign.  
   * Determine the country with the highest number of customers who accepted the last campaign.  
   * Investigate if there is a discernible pattern in the number of children at home and the total expenditure.  
   * Analyze the educational background of customers who lodged complaints in the last two years.
     
## Sources and Documentation
   * https://pandas.pydata.org/docs/index.html
   * https://numpy.org/
   * https://matplotlib.org/stable/
   * https://seaborn.pydata.org/index.html
   * https://scipy.org/
   * https://docs.python.org/3/
   * https://jupyter-notebook.readthedocs.io/en/stable/

## Usage
Open the notebook in Jupyter and run all cells in order.  Some dependencies are required on your machine (reference sources and documentation.)

