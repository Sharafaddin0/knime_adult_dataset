# knime_adult_dataset
This dataset known as "Census Income" cited in 1996. 
The source of the dataset: https://archive.ics.uci.edu/dataset/2/adult
Here we download dataset as zip file from given source, then transform and save it as CSV file.

![1_st part of project](https://github.com/user-attachments/assets/5801813d-8a81-483c-9266-fa8376b1afcc)


Here by importing the same CSV file, we will put it into DataBase and read this file itself.
DataBase will not accept "hypher-minus" symbol as column names, replace it with underscore "_".
Created database in PostgreSQL 17. 
There are multiple ways to query data from database, I showed some of them below.
At the end, I created some new data from given table and inserted into database itself.

![2_nd part of project](https://github.com/user-attachments/assets/a39b8cec-1c90-4aed-93d5-9ffba2a50607)

