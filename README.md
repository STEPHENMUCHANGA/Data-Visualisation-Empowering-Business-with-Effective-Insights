## Gain insights into leveraging data visualisations as a tool for making informed business decisions

### Table of Contents 

### Project Background

#### An online store has been performing well and the management, both CEO and CMO, want to examine major contributing factors to the revenue to strategically plan for coming finacial year.
#### The management interested in viewing the metrics from both an operations and marketing perspective, expand the business, and seek guidance to keep clear focus. 

### Research Questions 
##### Questions for CEO

1. How does sales vary across the countries?
2. What are the best selling days and months by quantity?
3. What are factors affecting demand of items across the countries?
4. What are ways to correct the trends in worst performing items by sales?? 

##### Questions for CMO

1. What are the general trends in sales by quantity?
2. What are the general trends in sales by country?
3. What are the best selling items by quantity?
4. What are the best selling items by revenue?

### Data Preparation

- Data was cleaned using data sorting function of MS Excel[Download here](www.microsoftoffice.com) to highlight negative data points because prices and unit quantities are supposed to have values of zero or above, and one respectively.
    1. Quantity Check: =IF(B2<1, "Invalid", "OK")
    2. Price Check": =IF(C2<0, "Invalid", "OK")
- Conditional formular logics were applied to hightlight and identify these data criteria.
- Data was transformed to get rid of bad data points.

##### Raw data
  ![Online retail- Raw data](https://github.com/user-attachments/assets/d8242fd0-0fd4-4ca0-9b5d-12d3cace9760)
 
 ##### Cleaned data
  ![Online retail- Cleaned data](https://github.com/user-attachments/assets/cbd9b007-f06c-4268-8a81-a6ff9b516756)

### Creating Visuals
- Visuals were created to provide the basis that answers the fundamental questions raised by both CEO and CMO

##### Revenue by Month
![Revenue by Month](https://github.com/user-attachments/assets/2b4a089a-90df-42e5-ac96-301b493547d8)

 ##### Quantity against Revenue by Country
![Quantity against Revenue by Country](https://github.com/user-attachments/assets/44ae642f-4032-4891-bc0a-6e5a54101fb1)

##### Sum of Revenue by Customer
![Sum of Revenue by Customers](https://github.com/user-attachments/assets/5c89874b-d3cb-4fde-ad03-6bbeba0236eb)

##### Sum of Quantity by Country
![Sum of Quantity by Country](https://github.com/user-attachments/assets/f8b62c19-c7ff-4974-bf1f-bb0487ec51b1)

### Data Analysis and Findings

-The data analysis and result presentation was up-to-date and free of errors

##### First Visual
- After loading it to PowerBI, data was cleaned and prepared using "Extract, Transform, and Load" model to choose appropriate data, manipulate to required standard and form, and load to the software for action.
- Revenue in the first 8 months was fairly constant, however, the revenue exponentially grew in the months of September (40%), October and November ($ 1.46M), then deeped in December ($ 0.43M).
- Thus, the retail is seasonal with its boom being at the end of the year.

##### Second Visual
- This shows opportunity of growth in demand for top 10 countries excluding U.K, which has already grown beyond others.
- Countries such as Netherlands, Ireland, Germany and France have high volumes of units bought and corresponding high revenues.
- Thus, these should be countries of focus to ensure maximum sales and revenue realization.

##### Third Visual
- The visual shows top 10 customers by purchases.
- There are minimal differences in purchases volumes between the top 10 customers, about 16% difference between top most and second top customer.
- This shows a balanced in spread of customers purchasing power, and the retail does not rely on one or few customers.
- Thus, the customers' bargaining power is low, hence the business is in a strong position.

##### Fourth Viaual
- The map shows regions of regions with most revenue generation likelihood.
- As observed, apart from U.K, Countries such as the Nentherlands, Germany, Austria and France are generating high revenue.
- The company should invest more in these countries and the region to maximize on the demands present for maximum revenue.
- The map shows high demand region being Europe, with America region having low demand, while Africa and Asia having almost no demand.
- The low or no demand regions of America, Africa and Asia need a new strategy from the company to boost demands in these regions.


### Conclusion and Recommendation 

- The CEO and CMO should pay attention to the insights provided to ensure better decisions are made.
- Necessary and appropriate strategies should be adopted to maximize revenue in the high-demand regions, and restrategize in the low-demand regions to realize the potential in those regions.
