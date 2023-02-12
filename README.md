# Project Name: Pharmaceutical-sales-analysis

# Introduction
Foresight Pharmaceuticals is one of the world’s leading pharmaceutical companies with markets across the different regions of the world. The company do not directly sell to customers but work with a couple of distributors in all their regions, and have agreement with each distributor to share their sales data with them to enable them gain insights of the markets.


# Problem Statement
The goal of this project is to uncover insights using the sales data from Foresight Pharmaceuticals to help the company make informed decisions. The dataset that used consists of sales data from the company’s two markets: Germany and Poland.

After looking critically at the dataset, i decided to provide answers to the following questions:
-	Which market has the most sales and what factor(s) may have contributed to that?
-	Which products lead sales and the ones that did not do well across both markets?
-	Which channel/subchannel lead sales?
-	What is the sales year over year change by channel?



# Data Sourcing
This dataset is a simulated datasets from real business data and published by Foresight BI & Analytics Global Solutions (Foresight BI), which is a Business Intelligence and Data Analytics firm. The dataset was downloaded from [Foresight BI website](https://foresightbi.com.ng/practice-data/3-datasets-for-your-portfolio/).


# Data Transformation
Data transformation was done using Power Query Editor in Microsoft Excel.
The following actions were taken to perform data cleaning: 
- Promoted headers: The first rows were made headers by applying “Use First Row as Headers.”
- The data types of each column were properly validated.
- The latitude and longitude columns were removed from the table, since it was not important to our analysis.

![](https://github.com/Inemesit1995/Pharmaceutical-sales-analysis/blob/main/Data_cleaning.png)



# Findings

![](https://github.com/Inemesit1995/Pharmaceutical-sales-analysis/blob/main/Dashboard.png)

The following are the findings from the analysis of the sales data:
- In analysing the sales data shared by each distributor with Foresight Pharmaceutical Company, it became clear that there were no sales in Poland in 2017, 2019 and 2020. This had a significant impact on the total sales made in Poland which stood at **5.77%** as against Germany's **94.23%**. One of the factors that contributed to this situation would have been that products were not delivered to distributors in Poland.

- The next point of notice is that the top 10 products with the highest sales were all from Germany while the bottom 10 products with the lowest were all from Poland for the years under analysis.

- In terms of the channel of distribution, pharmacy recorded the highest sales with **53.94%** in total sales. More sales were made via retail subchannel with about **4%** in sales ahead of institution.

- There was a **7.13%** increase in sales in sales in Germany via the hospital channel in 2018, but a **1.79%** and **-13.40%** in sales in 2019 and 2020 respectively. The sales representation in 2020 would have been as a result of the COVID19 pandemic.
