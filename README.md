### A little about me
🔭 I’m currently working on getting very comfortable with Cloud Technologies

🌱 I’m graduating very soon from Data Science at Columbia University!!!

👯 I’m looking to collaborate on data and statistics projects!

🤔 I’d love any suggestions on break-throughs in data science.

💬 Ask me about finance, operations and hospitality, happy to help!

📫 How to reach me: nadia.richards.nyc@gmail.com

😄 Pronouns: She/Her

⚡ Fun fact: I've lived in 4 different countries in my adult life. I'm now settled in the USA and have been here for the past 12 years. I love dogs and had a dachshund for a long time (can't wait to get another one). I love everything data related, seriously! 

### My Projects so far

# Visualization Project
So far I've done one project and working on my next one!
My first project involved analyzing large pieces of Data from 12 CSVs (from WHO, Our World in Data and Kaggle) to get correlation statistics between different socio-econimic factors and alcohol consumption in general and wine consumption in particular. I have background in Holistic Health, so I was mostly interested to see if wine consumption correlates with longer life expectancy. There is definitely more to look into, but what I have found so far is that life expectancy and wine drinking only have a low uphill correlation (both worldwide and in Europe - the highest wine drinking continent!). But both wine drinking and life expectancy are really highly correlated with country's GDP. So the most fitting conclusion with my reserach so far is to say that the higher the GDP of your country, the more likely you are to both live longer and drink wine. Things I worked on in the project were: Python, Python API, Pandas, Matplotlib, Numpy, Scipy Stats, Seaborn, Google Maps API. I became really good at merging CSVs, binning, boolean masks, regression and statistical analysis and much more!
Here is some visuals from my project! And feel free to [go here to see our Jupyter notebooks!](https://github.com/nadiarichards/data-analysis-project-1/tree/main/Finalized_project_work)
![](https://github.com/nadiarichards/data-analysis-project-1/blob/main/Finalized_project_work/Images/4_continent_boxplot.png)
![](https://github.com/nadiarichards/data-analysis-project-1/blob/main/Finalized_project_work/Images/wine_consumption%20as_%25_of_total_alcohol_consumption_per_continent_bar_graph.png)
![](https://github.com/nadiarichards/data-analysis-project-1/blob/main/Finalized_project_work/Images/wine_consumption_averages_by_continent_as_a_%25_of_total_worldwide_consumption_pie_chart.png)

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
