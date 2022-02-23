<p align="center">
	<a href="https://github.com/lboroWMEME-TeamProject/CCC-ProjectDocs"><img src="https://i.imgur.com/VwT4NrJ.png" width=650></a>
	<p align="center"> This repository is part of  a collection for the 21WSD001 Team Project. 
	All other repositories can be access below using the buttons</p>
</p>

<p align="center">
	<a href="https://github.com/lboroWMEME-TeamProject/CCC-ProjectDocs"><img src="https://i.imgur.com/rBaZyub.png" alt="drawing" height = 33/></a> 
	<a href="https://github.com/lboroWMEME-TeamProject/Dashboard"><img src="https://i.imgur.com/fz7rgd9.png" alt="drawing" height = 33/></a> 
	<a href="https://github.com/lboroWMEME-TeamProject/Cloud-Server"><img src="https://i.imgur.com/bsimXcV.png" alt="drawing" height = 33/></a> 
	<a><img src="https://i.imgur.com/yKFokIL.png" alt="drawing" height = 33/></a> 
	<a href="https://github.com/lboroWMEME-TeamProject/Simulated-Drone"><img src="https://i.imgur.com/WMOZbrf.png" alt="drawing" height = 33/></a>
</p>

------------

# Team CCC Project Documentation
The following repo holds all the code and documentation for the 21WSD001 - Team Project.

The project is split into 4 main parts
<div align="center">

||Description| Link|
|--|--|--|
| **Dashboard** | The GUI that will display the data from the cloud server |[GitHub](https://github.com/lboroWMEME-TeamProject/Dashboard) |
|**Cloud Server** | Handles all communication from the drones and to the end user| [GitHub](https://github.com/lboroWMEME-TeamProject/Cloud-Server)|
|**Drone Firmware** | Software to run the drone and sensors | GitHub |
|**Simulated Drone** | Software to simulate the drone sensors to test server and GUI | [GitHub](https://github.com/lboroWMEME-TeamProject/Simulated-Drone) |

</div>

*Stable versions of those modules have been linked to this repository but for the most up-to-date versions and individual documentation for those modules, visit the GitHub page using the links/buttons above*

----

## Table of Contents
- [Project Overview](#Project-Overview)
- [Development Plan](#Development-Plan)
- [Budget](#Budget)
	- [Current Expenditure](#Current-Expenditure)
	- [Future Expenditure](#Future-Expenditure)
- [Inventory List](#Inventory-List)
- [Test Plan](#Test-Plan)
	- [Server](#server)
	- [GUI](#gui)
	- [Actual Drone](#actual-drone)
	- [Simulated Drone](#simulated-drone)

----

## Project Overview
This project aims to create a module that can be fitted to a drone to aid first responders in disaster relief by providing them with useful data so that they can properly assess the risk of an area post-disaster and, effectively implement a relief strategy in oder to reduce the time and risk taken by responders.

Disaster preparedness and awareness has taken centerstage around the globe and if the response to COVID is any indication, it is clear to see countries are hilariously underprepared to properly handle disasters. 

Although, this project does not aim to ease the response to pandemics it aim to ease the response to disasters such as, radiation leeks, hazardous chemical spills, earthquakes, floods, fires and other physical disasters where sending in people would be dangerous due to the lack of data on how hazardous the situation is currently.

Usually, a team of people is sent in to the area of interest to collect data and identify how best to proceed. However, this puts them in an unknown amount of risk. Our module can be attached to a drone to that can be sent ahead of the team to analyse the situation faster and safer rather than risking peoples lives.

The drone is fitted with a range of sensors such as, a geiger counter, gas detector, temperature sensors, particulates detector and, thermal and object detection cameras. All of which will feed data back to a central server which can then be viewed by the user though the dashboard. 

They can then use this data to plan an effective response strategy for the situation at hand. The drone will give them all they data about what parts are the most dangerous, what parts are fine all without endangering the user themselves.

----

## Development Plan
The initial stage of the project requires an identification of requirements from the stakeholders. From these requirements the functionalities of the drone's main systems and subsystems can be determined. Below are the stakeholders involved in this project:
<div align="center">

|Categorisation|Stakeholder(s)|
|--|--|
| **Primary** | Operators. Emergency services |
|**Secondary** | Civilians |
|**Tertiary** | Government. Lecturers. Technicians. Maintenance |

<div align="left">	
From the above stakeholders the following requirements of the system were generated:
	
Operational:To collect data and compile into the interface for the user to view data regarding the state of the disaster zone, the location of survivors, and a map of the safest             route to the survivors 
	
----

## Budget

<div align="center">

### Current Expenditure

| Item 	| Supplier 	| Date Ordered | Date Received | Cost |
|:--:|:--:|:--:|:--:|:--:|
| [MLX90540 Thermal Camera](https://shop.pimoroni.com/products/mlx90640-thermal-camera-breakout?variant=12536948654163) | Pimoroni | 16 Dec 2021 || £54.00 |
|[Enviro+](https://shop.pimoroni.com/products/enviro?variant=31155658457171)| Pimoroni | 16 Dec 2021 ||£48.00|
|[Geiger Counter](https://thepihut.com/products/geiger-counter-kit-radiation-sensor)| Pi Hut | 16 Dec 2021 || £96.60 |
||||**Total Cost**| **£198.60**|

### Future Expenditure

| Item 	| Supplier 	| Cost |
|:--:|:--:|:--:|
|[NVIDIA Jetson Nano](https://www.robotshop.com/uk/nvidia-jetson-nano-2gb-development-kit-w-wifi-bundle.html)| Robot Shop | £72.59 |
|[PMS5003 Particulate Matter Sensor](https://shop.pimoroni.com/products/pms5003-particulate-matter-sensor-with-cable)| Pimoroni | £24.90 |
|[Raspberry Pi Pico](https://shop.pimoroni.com/products/raspberry-pi-pico?variant=32402092294227)| Pimoroni | £3.60 |
|[Raspberry Pi Pico](https://shop.pimoroni.com/products/raspberry-pi-pico?variant=32402092294227)| Pimoroni | £3.60 |
|3D Printing Budget| Loughborough University | £25.00 |
|PCB Fabrication| Loughborough University | £20.00 |
||**Total Cost**| **£149.69**|

**All prices include VAT @20%**

*These numbers do not include kit received from the university*

</div>

----

## Inventory List

<div align="center">

| Item 	| Where is/Who has it 	| Date Received | Date taken From Locker|
|:--:				|:--:		|:--:		|:--:		|
| Raspberry Pi 3 + Accessories	| Yaa	 	| 12 Nov 2021 	| 14 Jan 2022	|
| Raspberry Pi 3 + Accessories	| Jen		| 12 Nov 2021 	| 17 Dec 2021	|
| Raspberry Pi 4 + Accessories	| Ajay 		| 12 Nov 2021 	| 10 Dec 2021 	|
| Raspberry Pi Pico		| Jen 		| 12 Nov 2021 	| 16 Feb 2022 	|
| Track Robot			| Dev 		| 12 Nov 2021 	| 17 Dec 2021 	|
| XT60 Battery			| Locker 	| 12 Nov 2021 	| 		|
| XT60 Battery			| Locker 	| 12 Nov 2021 	| 		|
| XT60 Battery charger		| Locker 	| 12 Nov 2021 	| 		|
| Tetrix Robot			| Locker 	| 12 Nov 2021 	| 		|
| Raspberry Pi Cam		| Locker 	| 12 Nov 2021 	| 		|
| Logitech Camera		| Ajay	 	| 12 Nov 2021 	| 10 Dec 2022	|
| Tool Bag			| Locker 	| 12 Nov 2021 	| 		|
| Geiger Counter		| Jen 		| 03 Jan 2022 	| 16 Feb 2022	|
| MLX90540 Thermal Camera	| Locker 	| 12 Jan 2022 	| 		|
| Enviro+			| Locker 	| 12 Jan 2022 	| 		|

</div>

----

## Test Plan

*The Simulated Drone project was created explicitly to test the server and GUI without the actual drone needing to be present. This way, development for both those parts of the system can commence even before parts for the drone were ordered.*

<div align="center">

### Server

|Objective|Testing Strategy|Expected Output|Current Output|Pass/Fail|
|--|--|--|--|:--:|
|Show the GUI when a user visits the home URL `/`|Use a web browser to visit the home URL and observe the result|The dashboard should be shown and the user should be prompted to login|The dashboard is shown and the user is prompted to login|:heavy_check_mark:|
|Return a JSON object filled with the drones that are currently connected to the server when a GET request is processed on the `/drones` endpoint|Use the built-in API endpoint tester to send a GET request to the server and observer the result|The server should return a JSON object with the ID's of the drones connected to the server at any given point|The server does return a JSON object of the drones connected to the server|:heavy_check_mark:|
|Needs to add a new drone to the list of drones connected when a new drone connects to the server using the API endpoint ` /drones/{dname}`|Use the simulated drone tool to register itself with the server, then verify it's successes using the `/drones` API endpoint.|The server should return a JSON object indicating if it could successfully add a new drone to the connected drone list or not.|The Server returns a JSON object with a 200 status code indicating a success which can be verifiable using the `/drones` endpoint or the GUI.|:heavy_check_mark:|
|Needs to remove a drone from the list of connected drones when a drone disconnects using the API endpoint `/removedrone/{dname}`|Us the simulated drone tool to disconnect from the server, then verify it's successes using the `/drones` API endpoint.|The server should return a JSON object indicating if it could successfully remove the drone from the connected drone list or not.|The Server returns a JSON object with a 200 status code indicating a success which can be verifiable using the `/drones` endpoint or the GUI.|:heavy_check_mark:|
|Open a websocket with the drones ID when a drone connects and emmit the data the drone sends to the server to that websocket|Use the simulated drone tool to connect to and send data to the server then listen to the response on the websocket with the drone ID to see if the server echoes the data sent back.|The console of the simulated drone should display the data it sent to the server/The data should be shown on the GUI|The console does echo the data the drone sent and the GUI does show the data.|:heavy_check_mark:|
</div>

<div align="center">

### GUI

|Objective|Testing Strategy|Expected Output|Current Output|Pass/Fail|
|--|--|--|--|:--:|
|Display the drones that are connected connected to the server on the sidebar with their drone ID|Use the simulated drone to connect to the server and observer the result.|A new drone should show up on the side bar|A drone does show up on the side bar when a new drone connects|:heavy_check_mark:|
|Listen for data on the websocket of the selected drone|Use the simulated drone to connect a number of drones to the server and send data then select a drone and, see if the GUI displays the data in the console.|The data from the correct connected drone should appear in the console.|The data did appear in the console from the correct drone this will be displayed to the user using the GUI|:heavy_check_mark:|
|Display the data from the drone on the `Main` page of the GUI if the required format|Send data using the simulated drone tool and observe the page.|The data from the drone should appear in the main page. The feeds from the camera should be in its respective box's, the geiger dial should change depending on the reading. The other sensor values should be displayed correctly and graphs of the gas detected and the particulates detected should be plot.|Everything works as intended, the camera feeds are displayed in the correct box, the geiger dial changes with the data, the sensor values are displayed properly and the graphs are plotted as intended.|:heavy_check_mark:|
|Display the AI camera feed from the selected drone on the `AI Cam` page of the GUI|Send data using the simulated drone tool and observe the page.|A larger version of the AI cam should be shown.|Displays the AI Cam in a larger format.|:heavy_check_mark:|
|Display the Thermal camera feed from the selected drone of the `Thermal Cam` page of the GUI|Send data using the simulated drone tool and observe the page.|A larger version of the thermal camera should be shown|Displays the Thermal Cam in a larger format|:heavy_check_mark:|
|Display the Radiation history in CPM from the selected drone of the `Radiation History` page of the GUI|Send data using the simulated drone tool and observe the page.|Graph should be shown for the radiation in CPM|Shows Plotly.js graph that records historical radiation values|:heavy_check_mark:|
|Display the Pollution history from the selected drone of the `Pollution History` page of the GUI|Send data using the simulated drone tool and observe the page.|A larger version of the pollution graph should be shown|A larger version of the pollution graph is shown|:heavy_check_mark:|
|Display the Gas history from the selected drone of the `Gas History` page of the GUI|Send data using the simulated drone tool and observe the page.|A larger version of the Gas graph should be shown|A larger version of the gas graph is shown|:heavy_check_mark:|
|Display the drone's position on the map and tag critical reading on the map using the GPS data from the readings.|Send data using the simulated drone tool and observe the page.|A map should be shown the the drones current location, and dangerous locations should be highlighted.|*Feature not implemented yet*|❌|

</div>

<div align="center">

### Actual Drone
Subsystem: Geiger Counter	

|Objective|Testing Strategy|Expected Output|Current Output|Pass/Fail|
|--|--|--|--|:--:|
|Connect to Raspberry Pi Pico|Obtain values directly from Pi Pico and printing them through **chosen software program**|The values should display on screen|Testing not yet implement|To be annouced post testing|

*Only parts of the test plan have been developed as some parts and sensors for the drone have not come. Once we receive the parts and validate how they work and their limitations a test plan will be drawn up for that relevant subsystem*

</div>

<div align="center">

### Simulated Drone

|Objective|Testing Strategy|Expected Output|Current Output|Pass/Fail|
|--|--|--|--|:--:|
|Connect to the server|Get the drone to connect to the correct server endpoint then verify its connection using the API testing tools/GUI|A new drone should show up on the server|The correct drone is added to the server list.|:heavy_check_mark:|
|Disconnect from the server|Get the drone to disconnect from the server using the correct endpoint then verify its status using the API testing tools/GUI|The drone should be removed from the server list|The correct drone is removed from the server list.|:heavy_check_mark:|
|Display the camera feed|Run the program and see if the specified camera feed is displayed|The correct camera feed to be displayed in the camera box|The correct camera that is specified in the code is displayed.|:heavy_check_mark:|
|Run the object detection neural network on the camera feed|Run the program and observer if it detects objects|Boxes should be drawn around the detected object and the object should be labelled|Boxes are draw around the object and are labelled correctly.|:heavy_check_mark:|
|Connect to the server websocket|Run the program and attempt to connect to the server.|The client should report that a successful connection was made|The client does report a successful connection|:heavy_check_mark:|
|Send the data packet to the server|Run the program, connect to the server and send the data. The data should be received by the server and sent to any GUI's connected. If the data is received by the GUI the it was successfully sent|The GUI displays the data correctly|The GUI does display the data correctly.|:heavy_check_mark:|

</div>




----


