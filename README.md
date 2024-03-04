# Performance Analytics Kimia Farma Business Year 2020-2023
Rakamin Academy Project Based Internship - Kimia Farma - Big Data Analytics - Feb 2024

## About Company
Kimia Farma is the oldest pharmaceutical company in Indonesia, established in 1817 under the name NV Chemicalien Handle Rathkamp & Co. The company has grown to become one of the leaders in Indonesia's pharmaceutical industry, providing integrated healthcare services, and is listed on the Indonesia Stock Exchange (Bursa Efek Indonesia). In 2020, the company changed its name to PT Kimia Farma Tbk.

## Project Background
As a Big Data Analytics Intern at Kimia Farma, this project involves evaluating the company's business performance from 2020 to 2023. This task includes importing the provided dataset into BigQuery, creating analysis tables based on data aggregation from the dataset, and creating a company performance analysis dashboard using Google Looker Studio. Finally, an in-depth analysis will be conducted to understand data trends and patterns, and recommend improvements or strategies based on the findings of the analysis.

## Importing Dataset to BigQuery
These are the steps in importing data to BigQuery:
1. Download the provided dataset to the local storage.
2. Create a new project in BigQuery with the name "Rakamin KF Analytics".
3. After creating the project, create a new dataset with the name "kimia_farma" inside the project "Rakamin KF Analytics" project.
4. Import the dataset from local storage that has been downloaded to BigQuery and name it according to the original file name.
<img width="951" alt="image" src="https://github.com/shintaputrim/Rakamin-Kimia-Farma-BDA-0224/assets/141910150/47d73b4f-840c-45f5-8b5e-32d33161c735">

## Table Analysis
This is the 1st table that has been created using a sql query in BigQuery, that will be used to create a dashboard in Looker Studio.

<img width="965" alt="image" src="https://github.com/shintaputrim/Rakamin-Kimia-Farma-BDA-0224/assets/141910150/2a36ab07-410a-4951-bb3d-2d3ebe003377">
<img width="965" alt="image" src="https://github.com/shintaputrim/Rakamin-Kimia-Farma-BDA-0224/assets/141910150/cf5af497-9282-4798-b666-9cd666ec2922">

This is the 2nd table that has been created using a sql query in BigQuery, that also will be used to create a dashboard in Looker Studio.

<img width="603" alt="image" src="https://github.com/shintaputrim/Rakamin-Kimia-Farma-BDA-0224/assets/141910150/8917d09d-76e9-4c0b-99e7-df34cd10c0af">

## BigQuery Syntax
This is a sql query to create an analysis table. please kindly click the following [link of BigQuery sintax of 1st analysis table](https://console.cloud.google.com/bigquery?sq=791496496445:679c24857495477f9394522ae2eb6e92):

<img width="621" alt="image" src="https://github.com/shintaputrim/Rakamin-Kimia-Farma-BDA-0224/assets/141910150/efabcd08-240f-4cd2-b345-9bdf4bb4cd96">

To make it easier to visualize the Top 5 Branches with the Highest Rating, but the Lowest Transaction Rating, then a second analysis table is made. please kindly click the following [link of BigQuery sintax of 2nd analysis table](https://console.cloud.google.com/bigquery?sq=228401707437:ae218b5c13ce4cd79df284bb3c255e41):

<img width="524" alt="image" src="https://github.com/shintaputrim/Rakamin-Kimia-Farma-BDA-0224/assets/141910150/698dd8d5-565d-450f-b5db-d1fdec15b9c8">

## Dashboard Performance Analytics
After the analysis table is created, it is linked to loooker syudio as a data source, and this is a dashboard that has been created using the previously created analysis table. For an interactive dashboard, please kindly click the following [link of Looker Studio](https://lookerstudio.google.com/reporting/d4871889-5e89-484c-bc99-8602d1b0a583):

<img width="900" alt="image" src="https://github.com/shintaputrim/Rakamin-Kimia-Farma-BDA-0224/assets/141910150/37447448-be4e-4814-a93c-0c8c65a22314">

### Based on the dashboard above, here are some insights have been derived:
1. **Stable Trend**: Total Nett Profit and Total Nett Sales are relatively stable from 2020 to 2023, indicating the consistency of the company's performance in generating profits and sales.
2. **Provincial Contribution**: West Java has consistently been the largest contributor in Nett Sales, indicating the importance of strategically focusing on this region to increase market share.
3. **Customer Engagement**: Although the total number of customers is quite large, the ratio of customers to transactions is not very high, indicating the potential to increase customer loyalty and retention.
4. **Rating Comparison**: The highest-rated branches do not always have equivalent transaction ratings, indicating the potential to improve customer experience at the transaction level.
5. **Growth Potential**: Provinces outside of West Java, such as North Sumatra and Central Java, showed significant growth in Nett Sales, signaling business expansion opportunities in these regions.

### The insights mentioned above can also be transformed into marketing strategies as outlined below:
1. **Optimize Branch Performance**: Review the factors that influence the difference between branch ratings and transaction ratings for specific branches and implement strategies to improve customer experience at the transaction level.
2. **Focus on Customer Loyalty**: With a large number of customers, a stronger loyalty program can help increase customer retention and strengthen long-term relationships with customers.
3. **Regional Expansion**: Identify provinces with high growth potential, such as North Sumatra and Central Java, and allocate resources for business expansion and marketing in these regions.
4. **Customer Analysis**: Conduct further analysis of customer profiles and preferences to identify emerging market segments and customize marketing strategies and products according to their needs.
5. **Efficiency Improvement**: Review the operations of branches with low transaction performance to identify potential improvements in process efficiency and customer service.
