# **COVID-19 Project**
A SQL project with database creation, data cleaning, EDA with SQL queries, and deployed by creating an interactive dashboard using Tableau.
## Project Summary
Based on this COVID-19 dataset from Our World in Data, I followed the pipeline of:
- Some basic data clean up in Excel
- Create my own local MySQL database with the dataset
- Further data clean up and type conversion in MySQL
- Run queries to explore the data and get interesting insights
- Export data generated by MySQL to Excel files
- Use the data to create an [Interactive Dashboard](https://public.tableau.com/shared/RXNT2P2GH?:display_count=n&:origin=viz_share_link) using Tableau  

Some interesting findings:
- Global death rate peaked at the end of April in 2020 at a high 7.24%, and then slowly droped down to around 2.2% in December 2020.
- Europe had the highest death rate of 9.8% in the beginning of may 2020 out of all the continents, followed by a 6.3% of North America.
- With the very low percentage of population vaccinated and moderate high death rate percentage, China has a very low total death count.

All of these insights can be easily viewed on the interactive dashboard.
## Tools Used
MySQL, Tableau, Excel
## Data Science Techniques Used
Local MySQL database creation, Joins, CTE's, Aggregate Functions, Converting Data Types, Tableau Data Visualization, Interactive Dashboard Creation
## Files
- Covid project SQL script.sql (the SQL script that contains all the SQL queries as well as codes manipulating the SQL database)
- CovidDeaths.csv (raw data file1)
- CovidDeaths.csv (raw data file2)
- Tableau (folder containing excel files that are generated by SQL queries used to create the Tableau interactive dashboard)
## Usage
Link to the Tableau [Interactive Dashboard](https://public.tableau.com/shared/RXNT2P2GH?:display_count=n&:origin=viz_share_link)
## Data Source
The raw data used in this project was from [Our World in Data](https://ourworldindata.org/covid-deaths).