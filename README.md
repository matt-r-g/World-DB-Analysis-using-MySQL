# World Data Analysis using MySQL 🌍💻

Welcome to the **World Data Analysis** project! In this project, I worked with the **World** dataset and used **MySQL** to perform data analysis. The goal was to filter, sort and manipulate data based on specific queries to uncover insights about global information.

## 📈 Project Overview

This project explores a dataset containing global information such as countries, populations, regions, and other key metrics. I used **MySQL** to filter and return specific results from the dataset, employing various SQL techniques such as **queries**, **joins** and **clauses** like `WHERE`, `ORDER BY`, `GROUP BY` and more.

## 🛠️ Tools & Techniques Used

To analyse the data, I made use of several MySQL features and commands:

- **SELECT**: Used to select specific columns of data.
- **FROM**: Specified the tables from which to retrieve data.
- **WHERE**: Filtered data based on specific conditions.
- **LIMIT**: Limited the number of results returned to keep the output manageable.
- **ORDER BY**: Sorted data in either ascending (`ASC`) or descending (`DESC`) order.
- **GROUP BY**: Grouped data by specified columns to aggregate information.
- **JOIN**: Combined data from multiple tables using different join types (e.g., INNER JOIN, LEFT JOIN).
- **LIKE**: Filtered data using pattern matching.
- **OFFSET**: Skipped a number of rows before returning results for pagination purposes.

## 🔍 Key Queries & Insights

- **Filtering by Population**: Used `WHERE` to filter countries with populations greater than a certain threshold and ordered them by population size.
- **Country and Region Comparison**: Applied `JOIN` to combine country and region data, providing a clear view of how different regions perform globally.
- **Top 10 Largest Countries**: Used `LIMIT` and `ORDER BY DESC` to find the top 10 countries by population.
- **Region-Based Grouping**: Grouped countries by their region and calculated aggregate data, such as the average population within each region.
- **Data Pagination**: Applied `OFFSET` and `LIMIT` to paginate results, making it easier to manage large datasets.

## 📊 Visuals & Query Examples

Here are some example queries and visual results from the analysis:

### Example 1: A market research firm requires detailed information on cities beyond the top rankings for a comprehensive analysis. You're tasked with providing data on cities ranked between 31st and 40th by population to ensure a thorough understanding of urban demographics.


<img width="629" alt="Screenshot 2025-02-17 at 16 19 54" src="https://github.com/user-attachments/assets/81cc6c9a-2cf7-4232-a173-4d2517a0f8d5" />


### Example 2: A European cultural exchange program is seeking to connect students with cities across the continent. You're tasked with compiling a list of cities located in Europe from the database to facilitate program planning and student engagement.


<img width="628" alt="Screenshot 2025-02-17 at 16 23 17" src="https://github.com/user-attachments/assets/fc1e831f-9d5c-4828-9829-29f7ad8922a3" />


### Example 3: An urban planning committee needs to identify mid-sized cities suitable for infrastructure development projects. You're tasked with identifying cities with populations ranging between 500,000 and 1 million to inform their decision-making process. 


<img width="431" alt="Screenshot 2025-02-17 at 16 27 50" src="https://github.com/user-attachments/assets/49307e6a-d728-4e45-9467-4dab0e8deece" />


### Example 4: A demographic research team is conducting a comparative analysis of population distributions across countries. You're tasked with calculating the average population for each country from the database to provide valuable insights into global population trends.


<img width="585" alt="Screenshot 2025-02-17 at 16 34 06" src="https://github.com/user-attachments/assets/acb11d2f-ffc9-4d3c-bfa3-57ebdec18a1d" />


### Example 5: You're tasked with providing a brief overview of the most populous cities in the world. To keep the report concise, you're instructed to list only the first 10 cities by population from the database. 


<img width="570" alt="Screenshot 2025-02-17 at 16 35 28" src="https://github.com/user-attachments/assets/e712ece5-f6d6-42a8-bbe9-b57d21677689" />



## 💡 Conclusion

This project helped me improve my SQL skills and gain a deeper understanding of how data can be manipulated and analysed using relational databases. By applying various SQL commands such as JOIN, WHERE, GROUP BY and ORDER BY, I was able to extract meaningful insights from the World dataset.

Using MySQL for data filtering and aggregation is a powerful way to work with large datasets, and I hope this project can serve as a guide for others working on similar analyses.
