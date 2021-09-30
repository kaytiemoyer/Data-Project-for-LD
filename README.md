# Data-Project-for-LD
## Project Overview
The data basis of this project originated from 12/1/2020 and continued until 2/28/2021. The goal of this project was to define a set of metrics that could evaluate business problems and effectively analyze the data. I also analyzed specific characteristics pertaining to the Slot.ID, Creative.ID, and Device data.    
## Process
This process was completed on a Windows 10 system, with  Python 3.9.0 through Jupyter Notebook. 
#### 1.	Retrieving, cleaning and organizing the data. 
The data was downloaded from the associated Google document created by LD. NA values were dropped, and the columns Publisher.Split and Conversions were renamed to Cost and Profit for easier analysis. Dates were changed from the given format into a pandas dataframe that would be easier to work with but still understandable. The Profit and Cost metrics were calculated based upon the specifics given in the Google document; profits up to 1/7/2021 were 35 dollars each, and profits starting on 1/8/2021 were 40 dollars each. Revnue was calculated from this by subtracting costs from profit for each day of data. 

#### 2.	Completing basic analysis of the data. 
Profit versus Cost was visualized to display the cost of each day over the profits made. This was followed by a plot for Revenue, which displayed a more comprehensive image of how much profit the company made from December of 2020 to February. 

A third bar chart was made to illustrate the profits made from each device that was surveyed. This can show which devices are the strongest sources of profit. 

In addition, several data tables were made to show the highest profit garnering Creative.ID and Slot.ID, as well as the lowest performing IDs. Impressions and referrals were also considered with low performances in profits, to determine if the IDs could be useful in other ways.  

#### 3.	Further detail of the visualization
The visualization for profit versus cost indicates that overall, costs were typically always lower than profits. This was not always the case, and so the "true" revenue was calculated by subtracting the costs from the profits. 

The revenue plot indicated the same results, that the profits were typically higher than the costs. There were a few moments where the costs outweight the profits, and analysis should be performed more indepth where possible to indicate if recurring costs or problems that are causing this can be rectified. 

The profit by device bar chart displayed that mobile devices bring in 100% more revenue then desktops. Tablets earned the least amount of revenue from December 2020 to February 2021, at less than 15% of desktop's profit margin. "Other" was an option, but it held no occurrences of being used. 

The table with Creative.ID and profits looked at how much profit each assigned Creative.ID brought in. This was limited to the top ten, but could be modified to show any number desired. The revenue column was also included to show the difference between the profit and the revenue after costs had been subtracted. 

A table was also created for the lowest performing Creative.ID. This was again limited to ten, and with the combination of no impressions (user views) or referrals (user clicks), these creative ID's should be analyzed further to determine if they are worth maintaining. 

Similar tables were developed for highest and lowest performing Slot.ID. Once again, those that weren't bringing in profit could be considered beneficial in other ways, so impressions and referrals were included. Highest performing Creative.ID and Slot.ID, once identified, could be helpful in comparation to low performance ones to determine if there is a solution to improving the impressions, referrals, or profit. 

Finally, two tables were created to display the highest referral Creative.ID and Slot.ID. Each of the ten shown demonstrated some income, but the high amount of impressions and referrals can give exposure and meet customer goals in other ways. 

In the future, further analysis on the performance metrics of successful and unsuccessful Creative.ID and Slot.ID can help to increase profits for LD. Overall, the data indicates positive turnover for revenue with LD. Cost analysis could provide insight into dates when the profits did not outweight the costs, and give a better display of whether those dates are cause for concern or could be prevented. 

