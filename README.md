# US-house-prices-predictions
 US house prices predictions ml model
 
## Goal:
* **Leverage public available data to predict house pirces evolution in the US**
 
## Steps:
* Load the data
* Clean, transform and merge the data
* Create a basic machine learning model
* Estimate the accuracy of the model
* Run diagnostics to figure out how we can improve

Feel free to check the full list of steps in details within this **[Jupyter Notebook](https://github.com/Oussamahajoui/US-house-prices-predictions/blob/main/UShouseprices.ipynb/ 'US House Prices Notebook')**

## Findings:
My model did not perform exceptionally well, with an accuracy of only **~0.59** - *only slightly better than toss of a coin* -

As there is room for improvement, improving the accuracy either by adjusting to Yearly/Quaterly trends will be a good possible next step. 

Following is a chart showing in Green the correct prediction vs in Red the wrong ones:

![image](https://user-images.githubusercontent.com/83676274/191047579-053ff5a6-af2e-4aa3-a0a6-00c58b2ec7dc.png)

As you can see there is still much work to do in order to improve the accuracy of the model, **especially in the post 2018 era.**

Finally, based on our analysis the factors to predict house prices in order of importance are:
1. adj_value
2. adj_price
3. Vacancy Rate
4. Interest
 
 ## Data Sources:
**Federal reserve data:**
1. [CPI dataset](https://fred.stlouisfed.org/series/CPIAUCSL/ 'CPI dataset' ) - *CPIAUCSL.csv*
2. [Rental vacancy rate](https://fred.stlouisfed.org/series/RRVRUSQ156N/ 'Rental vacancy rate') - *RRVRUSQ156N.csv*
3. [Mortgage interest rates](https://fred.stlouisfed.org/series/MORTGAGE30US/ 'Mortgage interest rates') - *MORTGAGE30US.csv*

**Zillow data:**
1. [ZHVI (raw, weekly)](https://www.zillow.com/research/data/ 'Zillow Data') - *Metro_zhvi_uc_sfrcondo_tier_0.33_0.67_month.csv*
2. [Median sale price (raw, all homes, weekly)](https://www.zillow.com/research/data/ 'Zillow Data') - *Metro_median_sale_price_uc_sfrcondo_week.csv*



###### *Made by Oussama Hajoui*
