# PyBer_Analysis
Create an overall snapshot of Pyber's ride-sharing data.

## Challenge Overview
- For the first part, create a summary DataFrame that showcases the following for each city type:
    - Total Rides
    - Total Drivers
    - Total Fares
    - Average Fare per Ride
    - Average Fare per Driver
- For the second part, create a chart that plots the sum of the fares for each city type.

# PyBer data summary analysis:
- As city density increases (Rural to Suburban to Urban):
    - The number of rides given substantially increases.
    - The number of drivers available also substantially increases.
    - The total fares brought in increase.
    - The average fare per ride is higher in the more rural areas than urban areas.
    - The average fare per driver is also higher in more rural areas than urban areas.
- Implications:
    - There is greater demand for rides in more densely populated area, but there are also a much larger supply of drivers available. In rural areas there is almost a 2 to 1 ratio of rides to drivers compared to urban areas where it's the opposite, closer to a 1 to 3 ratio of rides to drivers. This means that each fare will be cheaper for the rider but also less profitable for driver in an urban area than compared to a rural area. Even though each driver is bringing in more money per ride in rural areas, the total rural fares brought in is far less than in urban areas.
    - Unlike the balance in urban areas, in both rural and suburan areas, there are less drivers than rides given. I would recommend increasing the number of rural and suburban drivers available to see if the demand for total rides increases and thus brings more PyBer more fare money. 
    - The average fare cost is much higher in rural and suburan areas than urban areas. It would be valuable to know if the this limited by the number of drivers available and if this is limiting the demand for Pyber. 
    - Overall, I believe we could optimize the number of drivers available and the cost of the average fare to increase demand and total fare money brought to PyBer.

# Analysis of the sum of fares for each city type:
- In the first half of 2019:
    - Urban totals were the largest, suburban totals were about half of the urban totals, and rural totals were the least.
    - Urban fare totals increases from January to just before March (from about $16k to $25k) and then jumped around $23k until May.
    - Suburban fare totals saw their highest point just before March (about $15k) and saw lesser peaks in mid-January and mid-March. The data was trending back towards $15k as it approaches May.
    - Rural fare totals hovered close to $250. There was a slight peak just before March (around $450). They saw their highest point at the start of April (at $500). 
- Implications:
    - All three city types saw a jump in fare totals just before March and then fell off a litle. It would be good to look closer at what caused this jump to see if we could use this to our advantage in the future. 
    - Rural fare totals at the start of April saw a spike. We should also look into this as an important time to focus on.
    - Suburban fare totals seems to have mini peaks in the middle of every month and there was a large upward trend at the end of April. A deeper dive into this could be valuable information.
    - Urban fares saw a comparitively slow start to the year before leveling off. It seems like the busier time of year to focus on starts mid-February. 