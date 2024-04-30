# Team 5 Mist 4610 Group Project 2

# Team Name:
21479 Group 5

# Team Members
1. Rebecca Kenirey @rkenirey
2. Jonathan Adeyemo @JonathanTheDon
3. Doyin Adeyemo @doyinadeyemo
4. Abby Low @abbylow1
5. Rayan Merchant @rayanmerchant

# Description of Dataset
The data set represents the number of electric vehicles around the country. It was obtained from the United States Department of Energy catalog. The dimensions are used for groups such as vehicles and country of origin, and the measures are used as scales or values within groups/dimensions. The data is meant to show the increase in EVs throughout 2017-2023 and how the United States (as well as the world) is turning to electric vehicles for various reasons such as environmental stability and cost reduction. There are ten columns in the database which include the date when the car was purchased, county and state of where the vehicles are located, the primary use of the vehicle (if it was used for passenger or truck drivers), battery electric vehicles (BEVs), plug-in electric vehicles (PHEVs), electric vehicle total, non-electric vehicle total, total vehicles, and percent electric vehicle. Our group used the year and sum of EV data along with southeastern state information to show the increased trend in the data. Researchers, lawmakers, and analysts interested in electric vehicle adoption, market trends, and infrastructure planning could utilize this dataset for analysis and decision-making purposes. 


# Question 1
## Question: What are the top 5 states in the Southeast with the lowest amount of total electric vehicles?
<img width="468" alt="image" src="https://github.com/rkenirey/Project_2/assets/143122583/52b80556-d892-45d0-bbec-8bbedd307a39">

## Description and Analysis
The data given answers the question of the top 5 states in the southeast with the lowest amount of total electric vehicles (EVs). The data provides a yearly comparison of total EVs from 2017-2023. Due to the data still generating for the year 2024, we did not include this data as it would not show the trend that 2024 is going to have. EV use and popularity are on the rise and this data set allows us to see the states in the southeast that are falling behind in use and adaptation of EVs. The data is relevant to EV companies because it shows the markets that they can target for more potential sales, and it can also help tailor their marketing of EVs in those regions. The increasing popularity for EVs highlights the importance of understanding the regional trends in adoption. By analyzing our data, EV companies can identify different opportunities for market expansion and tailor strategies to address the specific needs and preferences in these regions.

## Manipulation
The dataset is filtered by state, year, and sum of electric vehicles. To effectively capture the right states, we changed the classification of some certain states to the southeast (AL, AR, FL, GA, KY, LA, MS, NC, SC, TN, and VA). This then allowed us to query a dataset that reflects southeastern states. We also filtered the dataset by years (2017, 2018, 2019, 2020, 2021, 2022, 2023) to capture the certain years that we wanted to show in the graph. Doing this allowed us to capture just a fraction of the overall data that we wanted to illustrate. Then we filtered the dataset by the sum of electric vehicles. This allowed us to get a holistic view of the electric vehicles in the dataset which in turn helped us answer the question being asked.


# Question 2
## Question: Based off of question one, these are the states in the Southeast that have the least amount of electric vehicles, and when did electric vehicles begin to peak? Was it before/during/after Covid-19?
<img width="468" alt="image" src="https://github.com/rkenirey/Project_2/assets/143122583/d65ecf81-1157-48dd-889e-e661cf068fc8">

## Description and Analysis
This map helps answer the question of which states purchased electric vehicles before/during/after COVID-19 of the 5 lowest states that have the lowest EV numbers. Before COVID, the number of EVs were so low that some states didn’t have any data. Following the COVID pandemic, there was a noticeable change in advertising campaigns that addressed global warming and climate change. Due to this, the increase in advertising about global warming and climate change caused the result of EVs to increase due to the effect of regulating people from going out during the pandemic. However, after COVID (specifically 2023 Florida) the number of EVs purchased looks like it had decreased due to EV are not something customers can buy every year, but a long-term purchase. After the initial surge in EV purchases after COVID, there was a natural stabilization as the consumer demand adjusted. Although, the long-term trends demonstrate that as technology continues to improve and the infrastructure expands, the EV purchases is likely to continue to rise steadily. If advertising keeps influencing customers to buy EVs, then the trend would be that these states will increase their numbers of EVs purchased. As people take more steps to a greener future, EVs will become a big part of that. This transition is poised to revolutionize not just the automotive industry, urban planning, and even global geopolitics. With innovations in battery technology enhancing range and charging infrastructure expanding, the future of EVs appears increasingly promising.

## Manipulation
This is a dashboard of combined maps of three sheets that have been filtered by years (2017, 2018, 2019, 2020, 2021, 2022, 2023), States, and sum of electric vehicles. To create the three different illustrations, the dataset had to be manipulated to filter the pre-COVID years (2017,2018, 2019), during covid year (2020), and the after covid years (2021,2022,2023). This allowed us to compare the total sums of electric vehicles across three different time periods. The dataset was also filtered by states in the southeast to provide information specific to the different states targeted. Then the dataset was filtered by the sum of electric vehicles to give a quantitative variable that we are testing for. By creating three separate sheets with different filters and manipulations, this made it easier to separate the visuals to better compare the three eras.


# Tableau Packaged Workbook
https://outlookuga-my.sharepoint.com/:u:/r/personal/rxk20105_uga_edu/Documents/Documents/MySQLWorkbench/Group%20Project%202/Project%202.twb?csf=1&web=1&e=GgZVtS
