# <p align=center>PyBer_Analysis
Pyber Challenge Repo

## <p align=center> Purpose of Analysis
* Gather and Summarize Data on three target markets
    * Recommend three options for addressing disparity between Markets
* Data Used for Analysis of Markets (Urban, Suburban, Rural)
    * Total Rides
    * Total Drivers
    * Total Fares
    * Average Fare per Ride
    * Average Fare per Driver
    * Total Fare by City Type
* Information is presented in written as well as visual format for description

## <p align = center>Information Breakdown</p>
![Summary of Information](https://github.com/CoryCMyers/PyBer_Analysis/blob/main/analysis/Capture.PNG)

When we look at the information for the total rides we see that

### <p align=center>Total Rides

   * The total number of urban rides is rought 2.5 times the number of suburban rides
   * The total number of urban rides is roughly 13 times the number of rural rides
      * If effort could be made in these markets to drive sales this metric could be improved
   
   * Possible Fix
      * Create Flex/Hot hours within driver app based on past/targeted usage volumes
      * Could help to shape behavior/habit flow
      * Establish these hours during normal times for Disabled/Elderly to prefer to travel to shops
   
### <p align=center>Fare per Driver
   
   * When the volume of driver increases the income per fare for the exponentially decreases]
   
   * Possible Fix
      * When there are several service areas next to each other, reactively in the app increase income per fare for
        drivers in lower volume areas that are adjacent to higher volume
      * Driver Diffusion will naturally raise their income as they spread out and should lead to increase driver 
        uptime
      * Ancilary benifit of decreasing response time to ride requests in all coverage area due to better distribution of drivers

### <p align=center>Fare per Ride
   
   * The average fare per ride has a almost linear increase
      * The rural fare being on average higher than the urban fare by ten dollars
   
   * Possible Fix   
      * Use ride request volume in area to lower price
      * Enable push notifications to app users to incentivize in app purchase
   
### <p align=center>Total Fares
   * While the rural and suburban markets show a fairly linear increase in fares when compared to total drivers
      * The results of the urban market show that there is an overabundance of idle drivers in urban areas not generating revenue
   
   * Possible Fix   
      * Create Home or Local metrics and assign on rate of income per fare for that area
      * Create ancillary location metrics that must be committed to ahead of time, with a premium paid for distance from home metric
      * Premium also paid based on reliability of fulfilling commitment to coverage of an area
   
### <p align=center> Total Drivers
   * The driver volume is too concentrated in urban settings and too diffuse in rural settings
   
   * Possible Fix
      * Incentivize traveling to a secondary service area to provide service in rural areas if primary inhabitance is a urban area or suburban area.
   
### <p align=center> Fare by City Type
   ![Fare by City Type](https://github.com/CoryCMyers/PyBer_Analysis/blob/main/analysis/Pyber_fare_summary.png)
   * When looking at the overall fares by city type we see that in some ways all of the market areas tend to move in a simliar pattern
      * If there were methods of incentivization in place to encourage moving between local markets to meet need we would be able to see a more gradual shift, and where one market began to decline the other would pick up to compensate for the lost business in the initial market.
