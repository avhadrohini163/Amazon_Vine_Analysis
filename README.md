# Amazon_Vine_Analysis
Module 16- AWS and Big Data
## Overview:
This project consists of analysis on amazon reviews of office products. The dataset was extracetd with ETL process using PySpark. The data ewas transformed and connected to an AWS RDS instance and loaded the transformed data into pgAdmin. Finally it was determined if there is any bias toward favorable reviews from Vine members in your dataset.

## Results:
- The results were observed from the tables loaded to postgres from Pyspark colab notebook. The tables are given below:
### Customers Table:
![customers_table](https://user-images.githubusercontent.com/92752935/155853224-7c8db43a-c630-457d-baaa-f493ec1dc3c2.png)

### Products Table:
![products_table](https://user-images.githubusercontent.com/92752935/155853245-0df5f4cb-b3ad-4030-b01d-8a441c7bcadf.png)

### Review id Table:
![review_id_table](https://user-images.githubusercontent.com/92752935/155853271-6a3c2695-517f-4b99-96bc-6132bb0da7f1.png)

### Vine Table:
![vine_table](https://user-images.githubusercontent.com/92752935/155853311-a2178a44-1692-4c31-be1a-b62be9906043.png)

### Vine Review Analysis:
After the Vine review anlysis following results were observed:
![image](https://user-images.githubusercontent.com/92752935/155853506-2b35cc4f-c581-481f-9803-1a6a4c660f16.png)

- Total of 430 paid five star reviews were observed out of total 969 total paid reviews.
- The 44.375% of the reviws were five star paid reviews out of total paid reviews.
- Total of 19211 unpaid five star reviews were observed out of total 43608 total unpaid reviews.
- the 44.0538% of the reviws were five star unpaid reviews out of total unpaid reviews.

## Summary:
- Out of total 44,577 total review only 430 were paid reviews. However this dataset can be analysed more taking customer table, products table into consideration.

