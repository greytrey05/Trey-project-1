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

What is the problem you are trying to solve?
How to convert casual riders to annual riders

How can your insights drive business decisions?
Compiling data will show some trends that might been discover or uncover to lead the marketing team toward a new target. 
A clear statement of the business task
The financial analyst has concluded that members were more profitable than casual ridders from their analysis, Moreno the director of the marketing team wants to know how to convert casual riders to annual member to do this I have to work with data to discover trends in order to answer the business question. 
Prepare
● Where is your data located?
Dataset is located in a open-source storage from motivate International Inc under licence. 
● How is the data organized?
The dataset is a structured data organise in rows  and columns  
The dataset is organized in 13 columns for the different 12 files, each columns contain the same organization. Ride_id, rideable_type, started_at, ended_at, start_station_name, start_station id, end_station_name, end_station_name, end_station_id, start_lat, start_lng,end_lng, member_casual
● Are there issues with bias or credibility in this data? Does your data ROCCC?
 Reliability: the data is from motivate international an external company, it is not reliable
Original the data is from motivate international for the use of a fictional company
Comprehensive: data uses geographic localisation for different type of ride and when there used it.
Current; data is from January 2022 to December 2022. Data is current as it had been updated monthly.
Cited:  
The credibility of this data can be questioned as there is not enough qualitative measurement. Is it not bias.

● How are you addressing licensing, privacy, security, and accessibility?
It’s a public dataset from a licensed organization available on an open-source the privacy of the purchase and ID client had been hidden to maintain data security 
● How did you verify the data’s integrity?
When going through the data I am unable to view names or purchase from costumer as it has been crypted 
•	How does it help you answer your question?
This will be helpful to answer the main problematic because I need to work with accurate data and in order to verify if I possess the right data, I need to check their integrity.
● Are there any problems with the data?
Cyclistic count a total of 600 stations across their location. In the dataset i can see number out of the range of 600 stations which means it needs to be clean in order to work with accurate data.
Process

● What tools are you choosing and why?
I am going to use excel, as it is a csv.file the readability of this data will be easier 
● Have you ensured your data’s integrity?
I checked header column on excel they were all matching, performed missing entries. The ids clients names have been crypted to ensure the data privacy. A lot of rows are empty which come into conflict to whether or not I will be able to end this project with accurate result.
•	Has your data been properly formatted?
Every trip-divvy files has been formatted in cvs files with the function save as in excel 

● What trends or relationships did you find in the data?
I discovered from the pivot table of January that the members are more important than the casual riders. Casual riders for this month tend to use  their ride longer than members others key aspect have to be taken into consideration.
-	Jojojoo
-	Oojojk
-	Ijijijiji
-	Ijjijioj
-	Ijijjijj
-	Uhuhu
How will these insights help answer your business questions?
This insight help us having a better understanding about our data and our main answer with that we can use our prediction about how members and casual member behave through the use cyclistic product.
● Calculate the mean of ride_length
SELECT 
# Analyze




# Share

I used Tableau to make the vizualisation check the link below

You can get access to my viz here:[LINK](https://public.tableau.com/app/profile/james.trey/viz/Cyclistic-GoogleAnalyticsProject1/Histoire1)

# ACT

## Conclusion

The data shows that **casual riders** take bike trips from Friday to the end of the weekend as opposed to **member** who takes bike trips more evenly spread throughout the week. Casual riders on average also take twice times longer for a single trip, starting their trips later in the day. Both casuals and members take bike trips primarily during the warmer months with a steep decline. What also have been discovered is that the prefer ride is classic_bike and docked bike for casual member and for member they mostly use classic_bike and electric_bike. 
With the discovery of they behaviour the marketing team can tailor a new program for casual and member to maximize the profit as Moreno wished it.
We can conclude that casuals riders on average use the Cyclistic bike services for leisure and not to commute from and to work. At the moment Cyclistic offers a single annual membership which does not benefit casual riders as they take trips on the weekends and during the warmer months.

### Additionnal data I could use to expand my findings?

* I could use the weather data to see if that has an impact for the use of cyclistic product
* Data for Special event as well in the area where cyclistic operates could be used 

