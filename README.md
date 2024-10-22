# concalc1
We are building a Construction Cost Calculator that estimates building costs for Project Homes and Individual Houses across five Australian locations: Adelaide, Brisbane, Melbourne, Perth, and Sydney.

Description for the Construction Cost Calculator:
We are building a Construction Cost Calculator that estimates building costs for Project Homes and Individual Houses across five Australian locations: Adelaide, Brisbane, Melbourne, Perth, and Sydney.
Key Features:
1.	House Type:
o	Options: Project Home and Individual House.
o	Project Homes tend to have lower costs and no availability for High Standard or Prestige Standard finishes.
o	Individual Houses have options for Basic Standard, Medium Standard, High Standard, and Prestige Standard finishes.
2.	Finish Levels:
o	Basic Standard, Medium Standard, High Standard, and Prestige Standard.
o	The cost per square meter varies significantly based on the finish level.
3.	Construction Methods:
o	Brick Veneer, Full Brick, and Timber Framed.
o	The type of construction impacts the overall cost of the project.
4.	Size Ranges (in square meters):
o	90/110 sqm
o	120/140 sqm
o	160/190 sqm
o	These size ranges are used to calculate the cost per square meter, but the calculator should accept custom input for the house size. The nearest available size range will be used for the calculation.
5.	Location:
o	Adelaide, Brisbane, Melbourne, Perth, and Sydney.
o	The cost per square meter differs for each location due to varying building costs in different regions.
6.	Cost Calculation:
o	For each combination of house type, finish level, construction method, size range, and location, the calculator should calculate the estimated cost based on the cost per square meter from the dataset.
o	If a custom size is input, the nearest available size range will be used.
7.	Error Handling:
o	If High Standard or Prestige Standard is selected for a Project Home, the calculator will display a message indicating that no data is available for those finishes.
o	If no matching data is found for a particular combination of inputs, the calculator will return a “No data available” message.
Dataset:
The Excel dataset contains combinations of:
•	House Types (Project Home, Individual House)
•	Finish Levels (Basic, Medium, High, Prestige)
•	Construction Methods (Brick Veneer, Full Brick, Timber Framed)
•	Size Ranges (90/110, 120/140, 160/190 sqm)
•	Locations (Adelaide, Brisbane, Melbourne, Perth, Sydney)
For each combination, there are minimum and maximum costs per square meter. These are used to calculate the estimated cost for a given project size. are you able to code something like this?
