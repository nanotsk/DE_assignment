Assignment 1

This task which needs to be done in python. assignment details are explained in python assignment.pdf file. Features explanations can be found in features.xlsx file, input dataset is provided in data.csv. Output file is contract_features.csv.

Solution is provided in python assignment.ipynb file. notebook can be run step-by-step. data is being processed using predefined functions. After parsing and analyzing json data and building requested 3 features, result data had been deduplicated and saved in contract_features.csv. after deduplication, output dataset size matches with the input dataset size. 



Assignment 2

This part consists of two tasks, tables creation (GP Assignment_DDL.txt) and sql queries (GP Assignment_DML.txt). Tables are created and designed according to the analysis purposes.

describing table designs:
 
1. customers table enables doing customer fast lookup by id and email, as well as managing data by countries. (use case of this partitioning will be targeting different marketing strategies to different countries)

2. products table enables doing fast lookup based on product name and category, which might be most common querying criteria

3. sales transactions table enables doing fast lookup based on purchase_date (e.g. for monthly sales analysis), customer_id (e.g customers purchase amount analysis), product_id (e.g for popular products sales analysis) as well as easing data manipulaton with partitioning (e.g archiving old transactions)

4. shipping_details table enables doing fast lookup based on transaction_id as well as shipping_date. partitioning by shipping_date helps to manipulate data properly (e.g archiving old shipments)

