# Netflix Movies & TV Shows Project

## Goal of the Project
As a frequent user of Netflix, I was interested in the type of content (movies and TV shows), top genres, and when and from where that content was added.

## About the Data
The data used was for all titles on Netflix, and was sourced from Kaggle. I then cleaned and organized this data in Excel (found as "netflix_titles_edited.xlsx") to clean and make the data easier to use in Tableau. More details about the Excel part of this project can be found in my Excel repository.

## About the Project -- Visualizations and Dashboard
1. Content Type -- this pie chart shows the percentage of Netflix content that is either movies or TV shows - movies make up almost 70% of Netflix's total content, with 6,131 titles. I used several **marks** - color and label for type of content, and the pie angle and percentage of total label for the count of content.

2. Titles by Country (bar chart) -- this shows the country that the title is from. For this, the dataset contained up to five countries - in order to clean the results for the purpose of this visualization, I selected only the first country and assumed it was the country of origin. The United States had the most titles. I also used **marks**, with the type of content (movie/TV show) separated by color, and labels for the count of each.

3. Titles by Country (map) -- this illustration was a different way to show the same data from the second visualization. Here, the map shows where the most content was found, organized from light to dark (using a **mark** for color) as the number of titles increased. The US followed by India created the most content.

4. Top Genres on Netflix -- this bar chart depicts the count of Netflix titles that belong to a specific genre. I was interested to see the kind of content that Netflix felt appealed most to their customers - dramas, followed by comedies, topped the chart. I used **marks** to label the title count and a color gradient from most to least titles.

5. Top Genres on Netflix (Movies & TV) -- I separated the dataset into movies and TV shows in Excel since I wanted some of the data to be separated. This allowed me to see the top genres for movies and TV shows separately. For the dimensions and measures, I selected the content type and genres, and the count of type of content to see which genres topped the charts.

6. Top Genres Dashboard -- I added visualizations #4 and #5 to a dashboard to show the top genres as a whole and broken down into type of content.

7. Top Movie Genres Added in 2020 -- Due to COVID, most people began streaming on Netflix more, for which reason I wanted to look at this year specificically as a **filter**, and saw which movie genres Netflix felt would appeal to customers during this time of possibly higher viewership. The top genres were drama and comedy.

8. Top TV Genres Added in 2020 -- I did the same visualization for TV shows, with the same **filter** for 2020. The top genres were international TV and crime TV shows, which was an interesting result.

10. Type of Content Added to Netflix Over the Years -- I wanted to see whether Netflix felt that it was more valuable to add movies or TV shows to their roster for their customers. This line graph illustrates that Netflix has added more movies than TV shows. It also shows that Netflix peaked in the number of content added in 2019, and has seen a decline since 2019-2020. To create this visualization, I changed the data type for the "date added" string to a date, and while the Excel dataset showed specific dates, I only selected the years for this visualization. I also added a filter for the year added so that users can focus on any year they would like.

11. Movie Duration by Genre -- To see which genres had the longest movie duration, I used the Excel sheet that I created myself that separated movies from the full dataset. I changed the **measure** for the duration data to an average number of minutes. This bar chart contains a **filter** for genre and shows that classic movies have the highest average duration of 114.83 minutes.

12. TV Show Length by Genre -- I did the same visualization for TV shows, with the Excel sheet that I created for TV shows. I changed the **measure** for the duration to an average number of seasons. With a **filter** for genre that allows for a nuanced focus for the user, classic & cult TV had the highest average number of seasons of 5.727 seasons.

# Airbnb Project

## Goal of the Project
The goal of this project was to help a hypothetical client become an Airbnb host, with the help of data that can help him decide where to buy a home and when to rent it out in order to make a profit. For this, some important data to look at included the location of the home, the number of bedrooms, and how much to charge per night.

## About the Data
The data used was for Seattle Airbnb rentals in 2016, including listing and calendar data, and was sourced from Kaggle.

## About the Project -- Visualizations
I first used an **inner join** to join the listing and calendar data for the Airbnb rentals on the listing ID.

1. Price per zipcode -- this bar chart shows the average price of listings by zipcode, which can be used to see where the client can purchase a home in a zipcode where they can charge a higher price per night. I used a **filter** for zipcode in order to allow the client to easily look for specific zipcodes. This data was visualized with a bar chart **sorted** in descending order. The chart shows that zipcode 98119 has the highest average price.

2. Map of price per zipcode -- this map illustrates the same data in a different way, of the average price of listings by zipcode. There are **labels** for the average price and the zipcode.

3. Revenue for the year -- this line graph visualizes the revenue for 2016 broken down by weeks, using **marks**, **labels**, and changing the **measure** of the data. This allows the client to see the best time to rent out his house to make the most money possible, and which weeks of the year he can stay there himself. This time series based on the price suggests that it is beneficial to rent out the house over the summer and during the December holidays.

4. Average bedroom price -- this bar chart shows how the number of bedrooms in the Airbnb affects the price. This suggests that the client should purchase a house with more rooms since he can charge a higher price (although this may have higher costs). Since the bedrooms was a numerical value in the data, I **converted it to a dimension** in order to see the number of bedrooms instead of each individual listing ID.

5. Distinct count of bedroom listings -- this table shows the competition that my client may face based on the number of bedrooms he has. I changed the listing ID **measure** to a **distinct count** so that the data is presented as a tally of the number of bedrooms, rather than each individual listing ID. This data shows that fewer bedrooms presents more competition since there are more listings. However, as the number of bedrooms increase, while there is less competition, there may be less demand. However, the listing's higher price may make up for it.

6. Dashboard -- finally, I put all the visualizations into a **dashboard** so that we can see all the data in one place.

# Video Game Sales Project
I created visualizations using different graphs and charts that involved understanding the data, using **Marks**, **Filters**, and **Sorting**, and I also created a dashboard.

I also used **Bins**, created **Calculated Fields**, and created visualizations for Video Game Sales, and I used **Joins** to look at complete data for my visualization of Employee Salary.

## About the Data
For this project, I used a dataset from Kaggle about video game sales, and another Kaggle dataset for Starbucks locations.

## About the Project - Visualizations and Dashboard
1. Global Sales by Year line graph -- this depicted the global sales of each genre of video games each year. Using **marks**, I added labels for the year where each genre reached its maximum sales (by selecting the Scope as line, so each genre would have a maximum value noted on the graph). I added a **filter** for Platform, so that if we wanted to see how each platform (eg. Wii or PlayStation) performed in each genre.

2. Global Sales by Genre bar chart -- this showed, in descending order using **sorting**, the best-performing genres of video games in a bar chart, with a **mark** for color of genre. Action performed best, and strategy performed the worst.

3. Dashboard -- I created a dashboard of the charts in Global Sales by Genre and Global Sales by Year to show a holistic display of the global video game sales.

4. Global Sales by Year (bin) stacked bar chart -- I created a **bin** for years, with a size of 5. This helped to create a stacked bar chart of the global sales categorized by genre, with the years divided into bins of 5 year spans. From this graph, we can see that 2005-2009 was the most successful for video game sales.

5. % of Global Sales stacked bar chart -- I used the bin I created for the Year data, and used the **quick table calculation** function to make the row data a Percentage of Global Sales. This helped me to see which genres of video games contributed to the largest percentage of global sales. For example, in 2005-2009, Action contributed to 6.06% (the largest percentage) of global sales.

6. Global Sales - EU Sales -- for this graph, I used a **calculated field** of Global Sales - EU Sales to compare how much sales differ when EU sales are removed. In 2010-2015, for example, the EU  contributed to 205.3m of action game sales.

7. Global Sales and North America Sales bar and line graph -- I combined global and North America's sales into one bar and line graph to show the relationship between the two of them.

8. Global Sales Pie Chart -- this pie chart divided the global sales by genre, showing that action games contributed to the most sales. For this, I used **marks** for genre (color and name), global sales (angle and label for sales).

9. NA Sales area graph -- this is a different way to visualize the data and based on the area of each color, we can see not only the increase or decrease in North America video game sales, but also the genres that created the biggest contribution to the sales for those years. For example, in 2009, Sports contributed $71.47m in sales and has a large area of the graph for that year. For this graph, I used **marks** for genre (color and label).

10. Starbucks location map -- using Starbucks directory data, I created a map using the longitude and latitude as the column and row, and postal code as the **mark** to create pinpoints of Starbucks locations. I then changed the mark to a **density map**, which shows that it is likely the metropolitan areas that have a greater density of Starbucks locations.

# Employee Salary (Joins) Project

## About the Project
### Creating the Join
The goal of this project was to use **joins** in Tableau.

The data for Employee ID in the dataset was incomplete, in that the Job Title and Salary sheets did not have all employee data, therefore using an inner join on Employee ID would result in incomplete data. I found this out by doing a right join, which resulted in null data for one row in the table, employee ID 1010.

Instead, I inner joined on employee ID for the Demographics and Job Title sheets (which had employee ID 1010 missing), but also joined on employee name for these tables, for which there was complete data. I also inner joined the Demographics table to the Salary table for a future visualization.

### Visualization
This visualization shows the employee name and their salary. For this, I created a bar chart **sorted** in descending order of salary, with a **mark** for color.
