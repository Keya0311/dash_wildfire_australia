# dash_wildfire_australia
# Data Description
This wildfire dataset contains data on fire activities in Australia starting from 2005. Additional information can be found here.
The dataset includes the following variables:

Region: the 7 regions
Date: in UTC and provide the data for 24 hours ahead
Estimated_fire_area: daily sum of estimated fire area for presumed vegetation fires with a confidence > 75% for a each region in km2
Mean_estimated_fire_brightness: daily mean (by flagged fire pixels(=count)) of estimated fire brightness for presumed vegetation fires with a confidence level > 75% in Kelvin
Mean_estimated_fire_radiative_power: daily mean of estimated radiative power for presumed vegetation fires with a confidence level > 75% for a given region in megawatts
Mean_confidence: daily mean of confidence for presumed vegetation fires with a confidence level > 75%
Std_confidence: standard deviation of estimated fire radiative power in megawatts
Var_confidence: Variance of estimated fire radiative power in megawatts
Count: daily numbers of pixels for presumed vegetation fires with a confidence level of larger than 75% for a given region
Replaced: Indicates with an Y whether the data has been replaced with standard quality data when they are available (usually with a 2-3 month lag). Replaced data has a slightly higher quality in terms of locations
# tasks:
Dashboard to display charts based on selected Region and Year
Objective:
The objective of this part of the practice assignment is to create dashboards to contain your plots and charts.

create a dashboard wherein the user can select the Region and the Year. Based on the selection, the dashboard will display the following two charts:-

Pie Chart on Monthly Average Estimated Fire Area
Bar Chart on Monthly Average Count of Pixels for Presumed Vegetation Fires

TASK 2.1 Add title to the dashboard

TASK 2.2 Add the radio items and a dropdown right below the first inner division

TASK 2.3 Add two empty divisions for output inside the next inner division

TASK 2.4 Add the Ouput and input components inside the app.callback decorator

TASK 2.5 Add the callback function

