# Trey-project-1
Google Capstone project: Case Study 1

# Introduction :

Cyclistic launched In 2016, a successful bike share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime. Cyclistic's has a flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members. Moreno director of marketing believes that maximizing the number of annual members will be key to future growth Rather than creating a marketing campaign that targets all-new customers

# Scenario :

You are junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company's future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently.

# The business task:

**Moreno** has assigned you the first question to answer: **How do annual members and casual riders use Cyclistic bikes differently?**

I will follow the steps of the data analysis process: **ask, prepare, process, analyze, share, and act.**


# Ask

1. Identify the business task: 
 
 * How do annual members and casual riders use Cyclistic bikes differently?
 
2. Consider key stakeholders

* Lily Moreno: The director of marketing


# Prepare


The data is on aws"amazon server" store in a public server [Divvy-tripdata](https://divvy-tripdata.s3.amazonaws.com/index.html)

I downloaded the previous 12 Months data and stored it locally. The data is reliable and original since it comes from the company.It is comprehensive, current, and cited. The data source is the company so everything about the users personal information is hidden or kept private to the company only.

Files names
202201-divvy-tripdata.csv 202202-divvy-tripdata.csv 202203-divvy-tripdata.csv 202204-divvy-tripdata.csv 202205-divvy-tripdata.csv 202206-divvy-tripdata.csv 202207-divvy-tripdata.csv 202208-divvy-tripdata.csv 202209-divvy-tripdata.csv 202210-divvy-tripdata.csv 202211-divvy-tripdata.csv 202212-divvy-tripdata.csv

The dataset is a .CSV files organized in 13 columns for the different 12 files, each columns contain the same organization. Ride_id, rideable_type, started_at, ended_at, start_station_name, start_station id, end_station_name, end_station_name, end_station_id, start_lat, start_lng,end_lng, member_casual.

# Process

Checked data for any duplicate
Checked for nulls entry


# Analyze

I used Excel to verify data consistency
Performed calculation of ride length using start_at – ended_at (min, mean and max)
Mode of the day using (=WEEKDAY) to match the day of the week
Used Pivot table to quickly calculate and visualize data 
* Calculate the average ride_length for members and casual riders.  = member_casual; Values = Average of ride_length  
* Calculate the average ride_length for users by day_of_week.  = day_of_week; = member_casual; Values = Average of ride_length.
* Calculate the number of rides for users by day_of_week by adding Count of trip_id to Values.

Used R to clean data and conduct descriptive analysis.
[R analysis](https://www.kaggle.com/code/treytrigga/google-capstone-project-1)

# Share

I used Tableau to make the vizualisation check the link below

You can get access to my viz here:[LINK](https://public.tableau.com/app/profile/james.trey/viz/Cyclistic-GoogleAnalyticsProject1)

# ACT

## Conclusion

The data shows that **casual riders** take bike trips from Friday to the end of the weekend as opposed to **member** who takes bike trips more evenly spread throughout the week. Casual riders on average also take twice times longer for a single trip, starting their trips later in the day. Both casuals and members take bike trips primarily during the warmer months with a steep decline. What also have been discovered is that the prefer ride is classic_bike and docked bike for casual member and for member they mostly use classic_bike and electric_bike. 
With the discovery of they behaviour the marketing team can tailor a new program for casual and member to maximize the profit as Moreno wished it.
We can conclude that casuals riders on average use the Cyclistic bike services for leisure and not to commute from and to work. At the moment Cyclistic offers a single annual membership which does not benefit casual riders as they take trips on the weekends and during the warmer months.

### Top Three recommendation

* Create a seasonal offer for single pass ride and full day pass ride on the beginning of hotter season from April to the end of september ex: 10-15 min free ride during hot season.

* As casual ridders are aware of cyclistic offer the marketing team can propose a week-end offer 

* create a credit membership where they use when needed this could drive profit  Ex: casual riders can opt to add money to their credit membership to buy a day trip.

### Additionnal data I could use to expand my findings?

* I could use the weather data to see if that has an impact for the use of cyclistic product
* Data for Special event as well in the area where cyclistic operates could be used 

