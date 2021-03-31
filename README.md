### A little about me
🔭 I’m currently working on getting very comfortable with Cloud Technologies.

🌱 I’m graduating very soon from an intensive Data Science Bootcamp at Columbia University!!!

👯 I’m looking to collaborate on data and statistics projects!

🤔 I’d love any suggestions on break-throughs in data science.

💬 Ask me about finance, operations and hospitality, happy to help!

📫 How to reach me: nadia.richards.nyc@gmail.com

😄 Pronouns: She/Her

⚡ Fun fact: I've lived in 4 different countries in my adult life. I'm now settled in the USA and have been here for the past 12 years. I love dogs and had a dachshund for a long time (can't wait to get another one). I've always worked with data and did complex analysis in all of my jobs, but now got an extra set of tools thanks to Columbia Engineering Data Science Bootcamp.

### My Projects so far (from last to first)
---
# Full Stack Healthcare Data Analysis Project

This project's main purpose was to make a full stack app that utilizes multiple tools including Python, SQL, Flask API and front-end work with HTML, CSS and JavaScript (Plotly, Leaflet, D3 libraries). We chose several datasets to achieve that specifically for healthcare revenue space. We originally pulled and cleaned data that had multiple data points to quantify value of care as well including readmission ratio in each facility based on different care categories (that table is in our PostreSQL, but we ended up not using it in our visualizations), clinical outcomes dataset  per facility/zip code as well as dataset with hospital-acquired infections. We have also explored more detailed Census data including poverty rate per zipcode as well as total population and it's racial distribution. We wanted to explore a deeper relationshios between multitude of those variables, but were limited with having to choose to present 3 visualizations as well as very limited timeframe. There is definitely space for further exploration within these topics. 

## Tools and Technology Used for Analysis

* Visual Studio Code
* Python
* Jupyter Notebook
* Pandas
* QuickDBD
* SQL
* PostgreSQL
* Census API
* JavaScript
* D3.js
* Plotly.js
* Leaflet.js
* MapBox
* CSS
* HTML
* Flask App

## Process Flow

1. CSV and API into Pandas
2. Cleanse data
3. Push data to SQL database
4. Create Flask API
5. Pull data into browser using JavaScript
6. Generate Dashboard using D3, MapBox, Plotly, and Leaflet
7. HTML and CSS formatting / organization

## Dataset Values Utilized and Ensuing Relationships (QuickDBD) 
![Screenshot](https://github.com/nadiarichards/project2/blob/main/Noah/QuickDBDv2.JPG)

## Dashboard Charts & Visualizations
![Screenshot](https://github.com/nadiarichards/project2/blob/main/Noah/first_third.png)
![Screenshot](https://github.com/nadiarichards/project2/blob/main/Noah/middle_third.png)
![Screenshot](https://github.com/nadiarichards/project2/blob/main/Noah/bottom_third.png)

---
# ETL Project

Worked on 6 CSVs from [Data.World](https://data.world/) to find information on Oscar-winning movies to get the data on the movies that have won Oscars since year 2000. Please see [my Jupyter notebook here.](https://github.com/nadiarichards/ETL-Project/blob/main/Nadia/Nadias_ETL_notebook.ipynb) What I wanted to look into was the following:
1. What was the rating from the critics vs IMDB rating of the movies that won Oscars.
2. How many of the movies that won Oscars were Animated ovies (cartoons).
3. Which directors created most Oscar-winning movies.
I had to the do the following transformations to the data to prepare it for the database:
1. Remove and/or replace NaN values.
2. Drop duplicates as some movies were showing up in the dataframes multiple times.
3. Used .iterrows to iterate through all the rows in a large datfarme to split the Genre column and count how many genres were attached to one movie and to see if Genre column contained the word "Animated" to create a boolean column for cartoons in the dataset.
4. Changed values in columns from "American" to "USA" and from "Yes/No" string to True/False boolean value.
5. Other things I did was: change column names, lowercase them, replace spaces in column names with the underscore symbol, reset index in the dataframe.
As the end result, I had created 5 tables in the Database in PosgreSQL, which we later joined on movie_title. 
Please see my Database image as well as final join code and output for the 5 tables in PosgreSQL.

![diagram](https://github.com/nadiarichards/ETL-Project/blob/main/Images/diagram.png/)

![join_tables](https://github.com/nadiarichards/ETL-Project/blob/main/Images/final_join_sql.png)

![join_tebles_output](https://github.com/nadiarichards/ETL-Project/blob/main/Images/final_join_output.png)

---
# First Python Visualization Project

So far I've done one project and working on my next one!
My first project involved analyzing large pieces of Data from 12 CSVs (from WHO, Our World in Data and Kaggle) to get correlation statistics between different socio-econimic factors and alcohol consumption in general and wine consumption in particular. I have background in Holistic Health, so I was mostly interested to see if wine consumption correlates with longer life expectancy. There is definitely more to look into, but what I have found so far is that life expectancy and wine drinking only have a low uphill correlation (both worldwide and in Europe - the highest wine drinking continent!). But both wine drinking and life expectancy are really highly correlated with country's GDP. So the most fitting conclusion with my reserach so far is to say that the higher the GDP of your country, the more likely you are to both live longer and drink wine. Things I worked on in the project were: Python, Python API, Pandas, Matplotlib, Numpy, Scipy Stats, Seaborn, Google Maps API. I became really good at merging CSVs, binning, boolean masks, regression and statistical analysis and much more!
Here is some visuals from my project! And feel free to [go here to see our Jupyter notebooks!](https://github.com/nadiarichards/data-analysis-project-1/tree/main/Finalized_project_work)
![](https://github.com/nadiarichards/data-analysis-project-1/blob/main/Finalized_project_work/Images/4_continent_boxplot.png)
![]<img src=https://github.com/nadiarichards/data-analysis-project-1/blob/main/Finalized_project_work/Images/wine_consumption%20as_%25_of_total_alcohol_consumption_per_continent_bar_graph.png>
![]<img src=https://github.com/nadiarichards/data-analysis-project-1/blob/main/Images/2_top_5_pie_chart.png>

