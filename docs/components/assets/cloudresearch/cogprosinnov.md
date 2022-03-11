**Problem IBM Trying To Solve**<br>
Prosthetics and robotic solutions work well in controlled lab environment but not in the real world (weather, terrain, geospatial location, visual recognition, etc). 
IBM has the technology to add AI and adaptive learning for a prosthetic device to function outside the lab environment

<img src="../../../../images/cog_prosth.jpg"  align="left"
		 style="width: 400px;"/>

**Components Used are:**
<br>***Watson Services / APIs:*** 
<br> Tone Analyzer, Speech to Text, Text to Speech, Conversation, Visual Recognition
<br>***On-prem:*** 
<br>MQ, DB2, Sensors, Prosthetics, Mobile, Car, Watch

<br>**CPI Stats Engine Component**
<br>- Provide multi-channel analysis to tune prosthetics based on known datasets
<br>- Provide meaningful interface to the patient. Interacts with patient based on where he wants to go that day and provide predictive tuning
<br>- Improve Lab Models and algorithms based on the feedback from the customer

<br>**CPI Real Time Engine Component**
<br>- Fine tune prosthetics with real time data collected from the sensors
<br>- Real time communication with the RT Engine
<br>- RT engine aynchronously communicates with the Stats Engine and exchanges data when connectivity is available

<br>**Case Study**
<br>- Sam a veteran with prosthetic leg need to drive a car to the grocery store
<br>- Macro predictions based on weather and geolocation asynchronously communicated to the prosthetics
<br>- Sam decides to meet his friend in the park full of grass not concrete
<br>- Micro predictions fine tune prosthetics based on analysis of sensor data



