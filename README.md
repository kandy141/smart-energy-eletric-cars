# smart-energy-eletric-cars
Problem:
-------------------------------------------
Determining correlation among factors for Electric Cars Adoption and calculate weightages of such factors using Machine Learning


Approach:
-------------------------------------------
 - Analyze factors contributing and come up with top k impacting ones.
 - Feed data for above k to a LightGBM model and get weights for the factors.
 - Output weights will give us a correlation between the top k factors by how much they are contributing to EV
adoption.

Factors explored:
-------------------------------------------
● Demographic
  - Mean Household Income
  - Education Attainment
  - Median Age
● Costs
  - One-time costs: Vehicle, Battery, Unit installations
  - Recurring costs: Maintenance, Insurance
  - Gasoline prices
● Incentives
  - Purchase/Tax/Registration Rebates
  - Parking Exemption
  - Lane Exemption
● Infrastructure
  - Charging Stations
  
  
  
Output (Light GBM Model results):
-------------------------------------------
 Upon feeding relevant data to light GBM model, top 5 factors which affect the electric cars adoption are (which are taken with high weightages):
      ● Charging_Station_count
      ● HOV_Lane_Exemption
      ● Educational_Attainment
      ● Purchase_Rebate
      ● Median_Age
   (Please see observations and results in Project.pdf)   
      
      
