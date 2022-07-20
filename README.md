# AIRLINES-DELAY-PROJECT
This is my submission for the NG30Days of learning capstone Project. 
DATA COLLECTION
The datset was gotten from https://github.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students/blob/main/Airline%20Project/Airlines.csv which was originally sourced from https://www.kaggle.com/datasets/jimschacko/airlines-dataset-to-predict-a-delay. 
# DATA CLEANING AND TRANSFORMATION
TOOLS USED:
Microsoft excel
Power bi
DATA CLEANING
The dataset was cleaned using Microsoft excel starting.The first step carried out was to duplicate the dataset and the duplicated copy was worked on. Using the find icon to check for empty cells, it showed that there were no empty cells in the dataset . The "TEXT" function was used to extract the days of the weeks from the numbers provided.
![Screenshot (8)](https://user-images.githubusercontent.com/107184353/179972377-923bea22-f7fd-48d0-865e-0094437cfe0f.png)

Then, the logical function "IF" was used to display the status of the flights as it was provided also in numbers.
![Screenshot (9)](https://user-images.githubusercontent.com/107184353/179972664-f644ac65-bf53-41ff-a75c-0683f45496ee.png)

Moving on , the dataset was sorted based on the number of flights in a descending order after which redundant information was seperated from the dataset. This was done by copying the following columns into different sheets, removing all duplicates and retaining the unique values.
1.Airline
2.Day of week

Then, the total flights daily and by each airline and was gotten using the "SUMIFS" function
![Screenshot (10)](https://user-images.githubusercontent.com/107184353/179973920-1616ec2e-739d-4d08-b634-9c235569e8fd.png)

![Screenshot (11)](https://user-images.githubusercontent.com/107184353/179973929-6a032e5e-41ac-41dc-bc63-848e964c8bce.png)

VISUALIZATION
All the data in each sheet were converted into tables and then imported into power bi for visualization. Two dashboards were created. The first dashboard is an anlysis on the daily delay of flights and  top 5 airlines with the  highest number of delayed flights. The second dashboard provides insight on the lowest number of delayed flights and undelayed flights.

# FINDINGS
This will be categorized into three
**GENERAL**
 43% of the total flights across all airlines were delayed with value of 558million
 OO airline had the highest number of flights and HA had the least
 Most delays in flights happened on Tuesdays and Wednesdays across all airlines
**TOP FIVE DELAYED FLIGHTS**
OO airline had the highest number of delayed flights despite being the airline with the highest third travelling distance and EV airline follows the same pattern
WN airline had the highest number of delayed flights by distance but the second highest by number of flights and the same pattern can be seen with DL airline
Based on the total time of flights, WN had highest delayed flights and OO airline comes in third place with EV airline having the least delayed flights.

![Screenshot (14)](https://user-images.githubusercontent.com/107184353/179991899-12b4d0be-29aa-40e5-8f74-e6e6b83fa9b2.png)

**BOTTOM FIVE DELAYED FLIGHTS**
HA airlines had the least delayed flights based on the travelling distance and and total time of travel.
Also, it was observed that the least delayed flights retained their positions regardless of the time and length of travel.

![Screenshot (15)](https://user-images.githubusercontent.com/107184353/179992205-b6d626c0-4780-4dc8-8e47-985ab89d560a.png)

# RECOMMENDATIONS
Airlines should reduce the number of flong distance flights because time reduction for such flights might be difficult as they are long distance travels
Airports and airlines should make preventive against flight delays and management plans for passengers  against Tuesdays and Wednesdays due to the high number of  delayed flghts
Also, airplanes that travel long distane should be well maintained becuase they contribute the most to delay in flights. Therefore , a fault will result in even        more delays
Above all, airlines and airports should always manage the number of flights relative to the time spent and distance travelled as this is the biggest factor in flight delays as shown in the analysis.





 
