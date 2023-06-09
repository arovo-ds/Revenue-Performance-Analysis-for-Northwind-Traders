# Revenue Performance Analysis and Data Visualization for Northwind Traders

### Objective
The objective of this project is to create an interactive Revenue Performance dashboard for Northwind Traders, a fictitious food import-export company; by querying its database which is also readily available and widely used by Microsoft to demonstrate the use of some of its packages such as Microsoft SQL Server management studio and Microsoft Access; to extract relevant data features sufficient to create the intended dashboard which would show visuals for the following:
> 1. The revenue distribution for the years of the business operation.
> 2. The revenue share by the countries where the business is operational.
> 3. Revenue share by the company’s sales representatives.
> 4. The top (10) products by revenue.
> 5. The product category revenue share.

It is noteworthy to mention that in an effort to showcase my proficiency with SQL, in this project, I perfomed exploratory analysis on the same Northwind Traders Database using SQL Queries on Microsoft SQL Server Management Studio by answering a few of a set of analysis questions originally set by the University of Ferrara, Italy, for analysis exercise on the Northwind Traders Database. Further information about this, including the questions, the SQL solution script and the solution files can be accessed [here](https://github.com/arovo-ds/Analysis-for-Northwind-Traders/tree/main/SQL%20query%20exercise%20and%20solutions).

### Methodology and Project Workflow
In order to successfully create the interactive revenue performance dashboard for Northwind Traders, I went through the following process:
> -	I obtained the readily available Northwind Traders database .bak file from [Northwind and pubs sample databases for Microsoft SQL Server](https://github.com/microsoft/sql-server-samples/tree/master/samples/databases/northwind-pubs).
> - I then ran SQL query on Microsoft SQL Server Management Studio to extract the necessary data features required to make up the dataset sufficient to produce the right visuals to answer the five executive questions outlined in the objective section of this readme.md file.
Below is the database diagram for Northwind Traders showing the various tables in the database:
![image](https://user-images.githubusercontent.com/90056014/224892945-729e76fd-8c8d-4404-bc35-9159d8e37ed5.png)
> - I loaded the created dataset into Tableau Desktop, and created visuals that answer’s the revenue questions above.
The SQL script I write to use in querying the database to create the needed dataset can be viewed using [here](https://github.com/arovo-ds/Analysis-for-Northwind-Traders/blob/main/SQL%20%20Database%20Query%20Script/SQL%20Query%20for%20Northwind%20Traders%20Database.sql).
The resulting .csv dataset created can also be viewed [here](https://github.com/arovo-ds/Analysis-for-Northwind-Traders/blob/main/SQL%20%20Database%20Query%20Script/Northwind%20Sales%20Dataset.csv).
> - Using Tableau, a data visualization package, I created the interactive executive dashboard for Northwind Traders.

### Final Result
Below is a copy of the created Northwind Traders' Interactive Revenue Performance Dashboard, which can also be viewed on Tableau Public in it's interactive mode: [Northwind Traders Revenue Performance Interactive Dashboard](https://public.tableau.com/app/profile/precious.arovo/viz/NorthwindTradersRevenuePerformanceDashboard/NorthwindTradersRevenuePerformanceDashboard)
![Northwind Traders Revenue Performance Dashboard](https://user-images.githubusercontent.com/90056014/226175859-c8945000-4849-4fdf-ab12-a555a2c01f93.png)

The .twbx tableau file can be downloaded [here](https://github.com/arovo-ds/Revenue-Performance-Analysis-for-Northwind-Traders/blob/main/Tableau%20File/Northwind%20Traders%20Revenue%20Performance%20Dashboard.twbx).
