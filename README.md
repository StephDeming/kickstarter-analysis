# An Analysis of Kickstarter Campaigns
performing analysis on EXCEL Kickstarter data to uncover trends

## Purpose
The purpose of this analysis was to help the client (Louise) understand how 
well her projects went in regards to the funding goals as well as the project
launch dates. 

## Analysis and Challenges
   In both outcomes based on launch date and outcomes  based on goals
she trended towards successful rather than failed. In order to perform the analysis
 on  "Outcomes based on Launch Dates" I created a pivot table to display the results.
Displayed on that the outcomes were further parsed down to months and separated 
according to "successful", "failed", "cancelled" and "grand total" as well as adding 
a filtering list above the chart. 

![Theater Outcomes by Launch Date SS](https://user-images.githubusercontent.com/90067477/134593802-b76527aa-bd2c-45c5-b382-8fd832c4da8c.png)

 I had difficulty in separating the content in the project guidelines. It took me time 
and going over the initial data to realize that I had divided the parent categories 
improperly. After deleting my charts and re-entering the data I was able to 
display what I was looking for. 
 
 In addition to the pivot table I created a line graph to display the "successful", "failed"
and "cancelled" outcomes over the same period of time. There is a gap in the graph for the 
month of October. I'm not sure why that happened. It's in the pivot table as well. 

 ![Outcsomes Based On Launch Date](https://user-images.githubusercontent.com/90067477/134593688-51426802-a72f-404d-8f67-8df038132e4c.png)

 In "Outcomes Based on Goals" I broke down the goals to $5000 increments and divided them according 
"Number Successful", "Number Failed", "Number Cancelled", "Total Projects", "Percentage Failed", 
and "Percentage Cancelled". using the COUNTIF function I was able to fill in that information. 
It was difficult to understand, it took me about two hours to understand what the formula was asking for,
especially when I was entering a greater than and less than statement. I also didnt realize how copying a 
formula on the row v. column would change the equation. 
 
 I made a "Outcomes Based on Goals" line graph. It showcases the number of projects that succeeded, failed
or cancelled along with the corrosponding goal. 

I struggled with making the percentage on the side. I honestly cant say what I did to fix it. I messed around
with the graph settings and made the situation worse for a while before I deleted it and started over. 
That fixed it!


![Outcomes_vs_Goals](https://user-images.githubusercontent.com/90067477/134593515-a4cefc1a-7b2a-4fdd-8db4-cdf895a48edb.png)


## Results

# What are two conclusions you can draw about the Outcomes based on Launch Date?
In the "Outcomes By Launch Date" category there was success rate of 70.2%.
May and June have a higher success rate than any other month and there were few cancelled
projects.  

# What can you conclude about the Outcomes based on Goals?
In "outcomes Based on Goals" there were more successful than failed projects.
The highest success rates fell in the $1000 to $4999(73%), $35000 to $39999(67%) and 
$40000 to $44999(67%) ranges; corrosponding with the lowest failure rates. 
The highest failure rates occurred in the <$1000(68%) and the $45000 to  
$45000 to $49999(100%) ranges. 

# What are some limitations of this dataset?
I understand it's a dataset so it won't take into account human error. But it doesn't take
unrealistic expectations into account. There are some projects what would be 
ludicrous to fund when looking at the summaries of them. 

# What are some other possible tables and/or graphs that we could create?
A bar chart could help with the visualization of the "Outcomes Based on Goals" sheet.
A combo chart could show more inclusive data. 
