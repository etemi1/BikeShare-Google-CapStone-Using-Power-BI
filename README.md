# Introduction
Welcome to the Cyclistic bike-share analysis case study! In this case study, you will perform many real-world tasks of a junior data analyst. You will work for a fictional company, Cyclistic, and meet different characters and team members. In order to answer the key business questions, you will follow the steps of the data analysis process: ask, prepare, process, analyze, share, and act. Along the way, the Case Study Roadmap tables — including guiding questions and key tasks — will help you stay on the right path.
By the end of this lesson, you will have a portfolio-ready case study. Download the packet and reference the details of this case study anytime. Then, when you begin your job hunt, your case study will be a tangible way to demonstrate your knowledge and skills to potential employers.
 
# Scenario: 
You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations.
Characters and teams


● Cyclistic: A bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day.

## ASK PHASE: 
  Three questions will guide the future marketing program:
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?


# Deliverable:
The Business Task is to use quality insights from my analysis to see how different customer types use bike share differently and recommend ways  Cyclistic can convert their casual members to annual members. 

## Data Souce:
https://divvy-tripdata.s3.amazonaws.com/index.html

## Data Cleaning:
  I imported all 12 csv into power Bi, dataset contained about 5.2million rows and 13 columns and all 12 csv had similiar structure. 
Each csv file contains monthly information about riders, So first thing i do is to load the files into power query of Power BI to transform the data, I joined all 12 csv into one and disabled the others from loading into the report environment.
After joining all 12 files together i commenced with the cleaning process, I deleted columns i didn't need for my analysis, changed data types to necessary data types,  i created a custom column ti calculate ride length, removed blanks where necessary. 


## Data Analysis & Visualization

1. How do annual members and casual riders use Cyclistic bikes differently?
   Annual members use bikes mainly on weekdays to commute to work and back from work,  while casual members use bikes mainly on weekends for leisure.  
   Casual members use docked bikes while annual members don't use docked bikes at all. Both casual and annual members use classic and electicr bikes. 
   Casual members top station incluced streeter DR, Michigan Ave, Millenium park and theatre on the Lake
   Casual members seem to have longer ride length compared to Annual members 
   Casual members make for 55% percent of total rides while annual members make up for 45% of total rides.
   Annual riders ride more consistently throught out the month except in May when casual riders had a peak month.
   
2. Why would casual riders buy Cyclistic annual memberships?
  Casual riders will buy Cyclisti membership if free trials are given so they can 
3. How can Cyclistic use digital media to influence casual riders to become members?
