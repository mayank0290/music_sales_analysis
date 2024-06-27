
# navigating music sales data using postgresql







## OVERVIEW 📜

PostgreSQL is a powerful, open-source object-relational database system. Here are some key points about it:

Purpose: It’s designed to safely store and scale complex data workloads.

Features:
Extends SQL with additional features.
ACID-compliant (ensures data integrity).
Supports custom data types and functions.
Highly extensible and customizable.
Runs on major operating systems.
Includes add-ons like PostGIS for geospatial data1.
Query Language: PostgreSQL uses SQL for querying and manipulation.


## EXTRACTING USEFUL INSIGHTS USING SQL 🎵📊


Total Invoices 📈:
To get the total number of invoices, you can use a simple COUNT query on the invoices table. 

Top Genres and Albums by Customers in Different Places 🌎🎶:
Join the customers, invoices, invoice_lines, and genres tables.
Group by city or country.
Aggregate the total sales for each genre and album. 

Top Artists and Songs 🎤🎶:
Join the artists, albums, tracks, and invoice_lines tables.
Group by artist and track.
Calculate the total sales for each artist and song. 

Amount Spent by Customers on Artists💰🎵:
Join the customers, invoice_lines, and artists tables.
Group by customer.


## ACKNOWLEDGMENT 🙇🏻‍♂️

We would like to express our gratitude to the following individuals and resources that contributed to the success of this project:

Stack Overflow Community 🛠️:
For providing valuable insights, troubleshooting tips, and solutions to various SQL queries.
Special thanks to the users who responded to our specific questions related to PostgreSQL and data analysis.

Power BI public 📈: We'll be going to use Power BI to visualize the data to make it more interactive and visualling appealing