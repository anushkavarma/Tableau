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

6. Global Sales - EU Sales -- Ffor this graph, I used a **calculated field** of Global Sales - EU Sales to compare how much sales differ when EU sales are removed. In 2010-2015, for example, the EU  contributed to 205.3m of action game sales.

7. Global Sales and North America Sales bar and line graph -- I combined global and North America's sales into one bar and line graph to show the relationship between the two of them.

8. Global Sales Pie Chart -- this pie chart divided the global sales by genre, showing that action games contributed to the most sales. For this, I used **marks** for genre (color and name), global sales (angle and label for sales).

9. NA Sales area graph -- this is a different way to visualize the data and based on the area of each color, we can see not only the increase or decrease in North America video game sales, but also the genres that created the biggest contribution to the sales for those years. For example, in 2009, Sports contributed $71.47m in sales and has a large area of the graph for that year. For this graph, I used **marks** for genre (color and label).

10. Starbucks location map -- using Starbucks directory data, I created a map using the longitude and latitude as the column and row, and postal code as the **mark** to create pinpoints of Starbucks locations. I then changed the mark to a **density map**, which shows that it is likely the metropolitan areas that have a greater density of Starbucks locations.
