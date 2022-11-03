# EMS-SYSTEM
this is an energy monitoring system
Machine-learning-open folder for the dataset & the python file.
In this project we create a resource optimization system with the help of machine learning attributes and some deep learning modules  . we also plotted several graphs using matplotlib , seaborn and chart_studio to make a better solution for the company . by this system we can improve our company better by predicting the future current of our device . since it is much more easier to find the difficulties that particular company .I’m damn surely saying that this project will definitely helpful in the big companies also. we also used other csv files,Matplotlib ,Seaborn ,Chart studio ,Skilearn Scikit Keras Time stamp API key for mapping Numpy’s and pandas
Predict employee attrition:
Procedures:
1. Understanding the business problem.
Energy management  is a huge problem across industries and  in household generally costs the company a lot for hiring, retraining, productivity and work loss for each employee who leaves. But our device definitely handle this problems.
2. Converting into a data science problem.
What can be done here is , we can build predictive model by supervised learning.
3. Exploring the data.(EDA)
Explorating the given data like the columns given by visualising or by getting the summary stats of the data.
Packages used here for this visulaization are seaborn, matplotlib and  powerbi .
4. Preprocessing of the data.
Preprocessing includes removal of un-necessary columns, filling the missing data & converting the data into appropriate changes.
5. Feature engineering.
Using the existing columns to create new columns.
Techniques
Fetch the data from the csv and using some python code and powerbi  and visualize the data  and predicting the next day current value using fbprophet module in python
  
Automated Energy Monitoring System(AEMS)
INTRODUCTION
Energy costs can typically be around 30% and upwards for the manufacturing industry. Our automated energy monitoring system addresses, ways in which energy utilization can be made efficient and in turn result in energy savings.
The objective of the product is to provide information about the energy usage of each device, which is used to audit the total energy usage and the generated tariff, in a resident or industry. 
The concept of the product is to create awareness among the consumers about their daily energy usage, so they can reduce the energy usage, which in return reduces the resources used for the production of electricity. 
Our real-time energy dashboard can make immediate changes in the consumption pattern and acts as a real-time energy audit tool. Each device can be remotely controlled in the webpage. 
Our solutions make it possible to bring in behavioral changes which create awareness amongst users and our sophisticated analytics, give insights on managing the energy better.

METHODOLOGY
•	The current sensor(ACS712-20A) is connected in series with the load (Appliance) to calculate the current consumption.
•	The voltage sensor(ZMP1018) is connected in parallel with the load (Appliance) to calculate the phase angle.
•	This phase angle is used to calculate the power factor for each device.
•	 
•	The analog data from the sensors is fed to the ESP 32 to process and find the rms value of the current and voltage.
•	With these values,  we find the power consumption.
•	Power consumption, along with the runtime of the machine is used to find the energy usage of the appliance.
•	These data are further processed to get accurate values.
•	The processed data is sent to the google sheets. The data from google sheets is used for analytics and act as a data feed to the Power BI for real time display of energy consumption.
•	This data is also used to monitor the tariff that is to be paid to the utility.
•	This process is updated in the Power BI every 12 seconds.
•	With ESP 8266, we create a web server, which is used to automate the devices connected to the AEMS to reduce the power consumption at no load condition. 
•	This method also breaks the circuit when it detects abnormal power consumption of the device and at power surges at the grid.
Machine-learning                                    -open folder for the dataset & the python file.
In this project we create a resource optimization system with the help of machine learning attributes and some deep learning modules  . we also plotted several graphs using matplotlib , seaborn and chart_studio to make a better solution for the company . by this system we can improve our company better by predicting the future current of our device . since it is much more easier to find the difficulties that particular company . we has also mentioned the distance between the place and also routed with powerbi .I’m damn surely saying that this project will definitely helpful in the big companies also. we also used other csv files,Matplotlib ,Seaborn ,Chart studio ,Skilearn Scikit Keras Time stamp API key for mapping Numpy’s and pandas




