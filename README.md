# Google-Data-Analytics-Professional-Certificate

**The first repository contains my certificate of completion for my first course in the Google Data Analytis course, Foundations: Data, data everywhere. 

*The second repository contains my first lab of the course. Lab 1. 

Inspecting a Dataset
As a data analyst, you'll use data to answer questions and solve problems. When you analyze data and draw conclusions, you are generating insights that can influence business decisions, drive positive change, and help your stakeholders meet their goals. 

Before you begin an analysis, it’s important to inspect your data to determine if it contains the specific information you need to answer your stakeholders’ questions. In any given dataset, it may be the case that:

The data is not there (you have sandwich data, but you need pizza data)
The data is insufficient (you have pizza data for June 1-7, but you need data for the entire month of June)
The data is incorrect (your pizza data lists the cost of a slice as $250, which makes you question the validity of the dataset)
Inspecting your dataset will help you pinpoint what questions are answerable and what data is still missing. You may be able to recover this data from an external source or at least recommend to your stakeholders that another data source be used. 

In this reading, imagine you’re a data analyst inspecting spreadsheet data to determine if it’s possible to answer your stakeholders’ questions. 


The scenario
Imagine you are a data analyst working for an ice cream company. Management is interested in improving the company's ice cream sales.

The company has been collecting data about its sales—but not a lot. The available data is from an internal data source and is based on sales for 2019. You’ve been asked to review the data and provide some insight into the company’s ice cream sales. Ideally, management would like answers to the following questions:

What is the most popular flavor of ice cream?
How does temperature affect sales?
How do weekends and holidays affect sales?
How does profitability differ for new versus returning customers?

Question #1: What is the most popular flavor of ice cream?
To discover what is the most popular flavor, I had to define what is meant by popular. Is the most popular flavor the one that generated the most revenue in 2019? Or is it the flavor that had the largest number of units sold in 2019? Sometimes your measurement choices are limited by what data you have—you can review your spreadsheet to find out if either of these definitions of “popular” make sense based on the available data.  The data provided did not include how many sales each flavor produced. However, we determined the data showed how much units of a flavor was sold, so we defined popular as the flavor that had sold the most units. In the flavors tab, we can see that chocolate, lemon and vanilla sold 20 units during the year. These were the most popular flavors. However, after making a visualization of the data, we can see that lemon sold 20 units four times during the year. This let's us see that lemon is the most popular flavor. 

Question #2: How does temperature affect sales?
To explore the second question, I click the temperatures tab and check out the data. The temperatures sheet has two columns and 366 rows of data. The column headers are temperature and sales. The data may show total 2019 sales per temperature (for instance, the first entry might sum up $36.69 in sales for three separate days that each had a high of 60 degrees). Or, the data may show  a snapshot of sales and temperature for each day in 2019 (for instance, the first entry might refer to a single day with a high of 60 degrees and $39.69 in sales). So, which is it? It’s probably a daily snapshot because there are 365 entries for temperature, and multiple rows with the same temperature and different sales values. This implies that each entry is for a single day and not a summary of multiple days. By analyzing the data we determine that average sales for the year is $52.10. The average sales when temperature is  50 degrees or lower is $49.91, -$2.19 below the yearly average. When the temperature is above 69 degrees the average sales are $63.07, an increase of $10.96 over the yearly average. When the temperature is over 79 degrees the average sales are $69.22, an increase of $17.11 over the yearly average. When the temperature is over 89 degrees the average sales are $79.13, an increase of $27.03 over the yearly average. We can clearly see a steady increase on the average of sales as the temperature rises. 

Question #3: How do weekends and holidays affect sales?
On the sales tab, we had to manually convert the data into weekends and holidays categories. We calculated the total average in sales, the weekend average in sales and the holiday average in sales. At first glance, you see that the averages are all within $2. However, when you calculate the total sales of the year and total sales on weekends, you see that total sales are $38,142.33 while total sales on weekends are $10,024.43. The weekend sales accounts for 26% of the total sales. The holiday sales accounts for 2.8% of total sales.  
