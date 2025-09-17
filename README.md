# Netflix Analytics Dashboard in Power BI

## Project Overview  
This project is an interactive Power BI Web dashboard built using the Kaggle Netflix Movies and TV Shows dataset (~8800 titles). The dashboard demonstrates data storytelling, KPI tracking, and interactive filtering using Power BI Service on Mac.

## Dataset  
- Source: [Netflix Movies and TV Shows – Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
- Records: ~8800  
- Fields include: title, type (Movie or TV Show), country, release_year, rating, duration, listed_in (genres), and description.

## Key Features  
- **KPI Cards**: Total Titles, Total Movies, and Total TV Shows  
- **Pie Chart**: Distribution of Movies vs TV Shows  
- **Map Visual**: Geographic breakdown of Netflix titles by country  
- **Drilldown Page**: Select a country on the map and view its Netflix titles in a table sorted by release year (latest to oldest)  
- **Interactive Filtering**: Visuals are cross-filtered so selections update other visuals in real time  

## Report Pages  
- **Page 1 – Overview**: Headline KPIs, distribution, and global map  
- **Page 2 – Country Drilldown**: Country-level exploration with a movie/show list ordered by release year  

## Skills Demonstrated  
- Power BI Web (Service)  
- DAX (Data Analysis Expressions) for counts and KPIs  
- Interactive dashboard design with cross-filtering and slicers  
- Data visualization and storytelling best practices  

## How to Reproduce  
1. Download the `netflix_titles.csv` dataset from Kaggle  
2. Upload the CSV file into Power BI Service (Web)  
3. Create visuals:  
   - Card visuals for KPIs  
   - Pie chart with type vs count of titles  
   - Map visual with country (location) and count of titles (size)  
   - Table visual with title, release_year, and type (sorted by release_year)  
4. Arrange visuals into an overview page and a drilldown page  
5. Export the report as a PDF for sharing or publish via Power BI Web link  



