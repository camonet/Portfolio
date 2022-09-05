# Data Science Projects
Each project title links to the project repository

## [Automated ETL pipeline](https://github.com/camonet/movies-ETL)
This project created an automated pipeline to extract raw movie data from Wikipedia (JSON format) and Kaggle (csv), transform it into a consistent structure, and then upload the transformed data into an SQL database. Creating the pipeline utilized Python, pandas libraries, SQL, PostgreSQL, and more. 
- The transformation step required using functions with various tools, including for loops, if else statements, lambda functions, and regular expressions to automate tedious and repetitive tasks, such as parsing the data and converting regular text into numbers.
- Connecting the script to an SQL database required creating a PostgreSQL database engine to automatically import the data into readable and clear tables. 

Example code 
> <img width="777" alt="Screen Shot 2022-09-03 at 11 41 37 PM" src="https://user-images.githubusercontent.com/99444856/188297714-97cd6cf0-4b3a-4dc8-8b0d-20f3986f9cea.png">


## [Manipulating Employee Information in pgAdmin](https://github.com/camonet/pewlet-hackard-analysis)
This project utilized various database managment techniques to model, engineer, and analyze data from large structured datasets containing employee information. Data modeling consisted of indentifying relationships between each of the tables to create an entity relationship diagram (ERD). In the data engineering phase a database was created, SQL queries were written to create tables, and the data was imported from CSV format. Import errors were also troubleshooted. Finally, analyis was carried out with intermediate level SQL queries utilizing multiple kinds of table joins, COUNT, GROUP BY, and ORDER BY functions, as well as the creation of tailored lists of employee information. 

## [Bikeshare Mapping in Tableau](https://github.com/camonet/bikesharing) | [Dashboard Link](https://public.tableau.com/views/Deliverable3_16604564417870/Start-UpPitchDeliverable3?:language=en-US&:display_count=n&:origin=viz_share_link)
Tableau Public was used to create a presentation for a fictional company to assess the viability of starting a bikesharing service in Des Moines, Iowa. To adequately tackle this challenge, publicly available data from CitiBike, a bikeshare service in New York City, was used. CSV files were imported into Tableau Public to create worksheets, dashboards, and stories for the final product. In this project, special consideration was placed on visualizing the data in a useful manner, which required knowing the audience, understanding their interests and concerns, and showcasing the data in a way that would satisfy their objectives and outcomes. 

## [Earthquake Mapping with JavaScript and APIs](https://github.com/camonet/mapping-earthquakes)
To show the differences in magnitude of earthquakes around the world, geographical coordinates and the magnitudes of earthquakes (geoJSON format) for the last seven days were retrived from [USGS's website](usgs.gov). Using  JavaScript, the D3.js library, Leaflet, Mapbox API's, HTML, and CSS, an appealing interactive map was created. Earthquake magnitudes are depicted with varying radii and color, and tectonic plate locations are shown. 

<img width="800" alt="Screen Shot 2022-09-02 at 5 09 19 PM" src="https://user-images.githubusercontent.com/99444856/188241292-5f019cbd-1be8-4fd9-bac9-5c3d4356a8c6.png">

- In the same repository, several different maps were created to showcase using different geoJSON polygon formats

## [Statistics and R](https://github.com/camonet/mechaCar_statistical_analysis)
This comprehensive project showcases R being used to perform various statistical analyses using structured and semi-structured datasets (in csv and JSON formats, as well as built in R datasets). Data was selected from each table using various functions, using bracket notation, using the $ operator, with logic, and with the subset() and sample() funcitons. The Tidyverse package was used to transform, group, and reshape data to suit the needs of the analysis. Functions used included mutate(), group_by(), summarize(), gather(), spread(), and more. To visualize data, R's ggplot library was used to create various graphs with different aesthetics. 
The analysis portion of the project required a working knowledge of different statistical test types, data types, data testing procedures (testing for normality, skew, etc), as well as understanding the results of statistical tests. 

## [Advanced Data Storage and Retrieval](https://github.com/camonet/surfs_up)
This project retrieved, anaylized, and visualized weather trends in Hawaii on a locally hosted application using SQLite, SQLAlchemy, and Flask. Python libraries pandas and matplotlib allowed us to analyse and visualize the data. SQLite was used to store Hawaii's precipitation data; an SQLAlchemy environment was initiated to connect to the SQLite database. The data was retrieved and saved in a pandas dataframe on jupyter notebook, where dataframe data was sorted based on a desired values, such as date. Selected data, such as precipitation trends was plotted using matplotlib. The summary statistics of the data were retrieved using df.describe(). Flask was then incorporated into data analysis to share data visualizations, and several routes were created to separate each portion of the project. 

## [VBA Stock Analysis](https://github.com/camonet/stock-analysis)
Using stock data for 12 stocks for the years of 2017 and 2018, a VBA macro was created to find the total daily volume and the yearly return for each stock. The macro could create pop-ups, input boxes, read, change, and format cell values. The project emphasized writing efficient and readable code by using for-loops, nested for-loops and conditionals. Additionally, the VBA macro measured the performance of code using VBA's Timer function. 
The figure below show how positive yearly returns were formatted in green and negative in red. A button was created to easily run the macro, and the input box is shown asking what year the analysis is to be run on. 
> <img width="541" alt="Screen Shot 2022-09-04 at 1 56 04 PM" src="https://user-images.githubusercontent.com/99444856/188329171-444c9897-2723-4877-8b33-8b6fad72a3e1.png">
> <img width="273" alt="Screen Shot 2022-09-04 at 1 56 42 PM" src="https://user-images.githubusercontent.com/99444856/188329193-19c056f8-d55c-4385-b2f3-e8851cdb8459.png">

## [Excel KickStarter Analysis](https://github.com/camonet/kickstarter-analysis)


> <img width="600" alt="Screen Shot 2022-09-04 at 1 59 47 PM" src="https://user-images.githubusercontent.com/99444856/188329318-0bb73f45-e1b0-4f50-92af-44e8eff41b96.png">

