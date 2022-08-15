# Kickstarting with Excel

## Overview of Project

Help Louise visualize the Outcomes of the plays based on their Launch dates and Funding goals.


### Purpose

Visualize the outcomes of the the plays based on their Launch dates and Funding Goals. Also, visualize the trends of the Outcomes based on the Goal Range.



## Analysis and Challenges

We performed 2 types of analysis based on the variables. The first one is to visualize the outcome based on launch date, and the second one is to visualize the outcomes based on Goals.

### Inferences

  * The most Successfull outcomes in the catogery of theatre are launched in the month of May. Also, The outcomes  based on the goal Range 45000-50000 are failed.

  * All the plays have either been successful or failed, but not canceled



### Analysis of Outcomes Based on Launch Date
 

years()  --- To extract the exact year of project Launched fron Date Created Conversion column of Kickstart data set

Pivot chart is created using the kickstart data set, using filters for Parent category because the focus of the outcomes based on the Launchdate is maily on Theatre.
Outcomes as Columns
Laumchdate as Rows

line Chart is created based on the Pivot chart which display 
Months based on the Launch dates on X-Axis
No. of Outcomes of Sucessful, canceled and failed events on Y-Axis

This line chart helps to Visualize the data and make inference of how the theatre outcomes performed over the years since the fundraising campaing initiated.


### Analysis of Outcomes Based on Goals

A new table is created with the ranges of the goals on the rows and No. of successful, failed and Canceled projects and their percentages on the columns
The No. of Sucessful, failed and canceled projects within the ranges of goals was extracted using the formula COUNTIFS()

Line chart is created with the values of percentage Successful, failed and canceled project on Y-Axis and range of the goals on X-Axis

This line chart helps visualize the data and make inference of the outome of the project within the range of the goal

### Challenges and Difficulties Encountered

Using COUNTIFS()

while using COUNTIF() and copying formula to the other feilds of the data set of the goal ranges if we dont change the outcomes to failed and canceled projects the entire count changes but outcome will be still for Successful projects


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The most successful projects were in the month of May
The most failed Projects were in the month of May

- What can you conclude about the Outcomes based on Goals?

The success percentage based on Goal range 45000-50000 was 0% hence the fail percentage at that goal Range is 100%


- What are some limitations of this dataset?
 
 The data could consist of more information related to failed and canceled projects. It would have been nice to have data spanning over few years. 


- What are some other possible tables and/or graphs that we could create?

	We could have visualized data in few other perspectives such as visualizing goal and pledged amount with the categories and sub categories, understanding the outcomes of the shows that had more backers, and the relation between the staff picks and the categories and the duration of the project  


