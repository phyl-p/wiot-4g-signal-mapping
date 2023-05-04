# wiot-4g-signal-mapping
A repo for visualizing 4G signal in the UVA E-school both in doors and outdoors. 

## 4G Signal Strength Mapping in UVA Engineering School
### WIoT Final Project Group 5

**Project Motivation**:
Long range signal transmission can have blind spots well within their proposed range–as we have seen for LoRa and BLE, where the theoretical range is a lot shorter or is significantly reduced due to the objects in the environment. LoRa has a proposed range of 3 miles in urban areas, but as shown in the results of the measurements in this class, it can have certain blind spots well within the 3 mile range, especially in underground settings such as basements. 4G/5G are important means of communication on Grounds, and they are relied upon for real time communication in case WiFi fails. Yet, it is sometimes reported that the 4G/5G coverage on Grounds is not ideal, especially in terms of underground environments. The Engineering School has a lot of buildings where the basements are environments where important experiments take place. Having robust and redundant communication is important for the safety of both the faculty, staff, students, and their work. Hence, we propose to measure the 4G/5G coverage in the E-School and around grounds. We will use various internet speed measurement apps on our phones to collect the data at specific geographic locations, indoors and outdoors. Using this data we can then create heatmaps for both indoor and outdoor settings, exploring the differences and enlightening the community to areas of low coverage.


System design figure: a high-level overview figure describing your proposed system.
Step 1: Identify applications with which to measure RSSI of 4G/5G
Step 2: Systematically measure 4G/5G signals in the E-school buildings, with an emphasis on basements, also record geographical coordinates for ease of future mapping/graphing.
Step 3: Plot the collected measurements on a geographical heat map to holistically present the data collected.

Work division: how you intend to divide the work among your group members.
Angelo: collect signal strength ~ location data 
Declan: collect signal strength ~ location data 
Phyl: collect signal strength ~ location data; graph a geographical heat map for signal strength measured. 


**This python notebook is step 3 of our project where we map the collected signal strength data**

Data Mapping Plan:
1. map data by type of sinal strenght (upload, download, rssi), floors and their coordinates.
2. Collect stats, such as mean, std, and range by floor, building and graph bar chart

### Conclusion:
We identify Wilsdorf basements, Thornton B wing, C wing D wing and Ewing a main signal blindspots. For more detailed analysis, see the statistical plots below. 

### Limitations:
Measurements were taken on different phones with carriers and different data plans. Upload and download rates are taken on two different iphones with T-Mobile and at&t as carriers and iphone 14 and iphone X respectively. The RSSI values are taken on a single android phone. Moreover, these data points are collect at different times of day and different days in the week, and for upload and download rates, only two measurements were taken for each floor for each location, and an average was taken of the two measurements.