<p align="center">
	<a href="https://github.com/lboroWMEME-TeamProject/CCC-ProjectDocs"><img src="https://i.imgur.com/VwT4NrJ.png" width=650></a>
	<p align="center"> This repository is part of  a collection for the 21WSD001 Team Project. 
	All other repositories can be access below using the buttons</p>
</p>

<p align="center">
	<a href="https://github.com/lboroWMEME-TeamProject/CCC-ProjectDocs"><img src="https://i.imgur.com/rBaZyub.png" alt="drawing" height = 33/></a> 
	<a href="https://github.com/lboroWMEME-TeamProject/Dashboard"><img src="https://i.imgur.com/fz7rgd9.png" alt="drawing" height = 33/></a> 
	<a href="https://github.com/lboroWMEME-TeamProject/Cloud-Server"><img src="https://i.imgur.com/bsimXcV.png" alt="drawing" height = 33/></a> 
	<a href="https://github.com/lboroWMEME-TeamProject/Drone-Firmware"><img src="https://i.imgur.com/yKFokIL.png" alt="drawing" height = 33/></a> 
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
|**Drone Firmware** | Software to run the drone and sensors | [GitHub](https://github.com/lboroWMEME-TeamProject/Drone-Firmware) |
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
|[PMS5003 Particulate Matter Sensor](https://shop.pimoroni.com/products/pms5003-particulate-matter-sensor-with-cable)| Pimoroni | £24.90 |
||||**Total Cost**| **£223.50**|

### Future Expenditure

| Item 	| Supplier 	| Cost |
|:--:|:--:|:--:|
|[NVIDIA Jetson Nano](https://www.robotshop.com/uk/nvidia-jetson-nano-2gb-development-kit-w-wifi-bundle.html)| Robot Shop | £72.59 |
|[Raspberry Pi Pico](https://shop.pimoroni.com/products/raspberry-pi-pico?variant=32402092294227)| Pimoroni | £3.60 |
|[Raspberry Pi Pico](https://shop.pimoroni.com/products/raspberry-pi-pico?variant=32402092294227)| Pimoroni | £3.60 |
|3D Printing Budget| Loughborough University | £25.00 |
|PCB Fabrication| Loughborough University | £20.00 |
||**Total Cost**| **£124.79**|

**All prices include VAT @20%**

*These numbers do not include kit received from the university*

</div>

----

## Inventory List

<div align="center">

| Item 	| Where is/Who has it 	| Date Received | Date taken From Locker|
|:--:				|:--:		|:--:		|:--:		|
| Raspberry Pi 3 + Accessories	| Yaa	 	| 12 Nov 2021 	| 14 Jan 2022	|
| Raspberry Pi 3 + Accessories	| Ajay		| 12 Nov 2022 	| 17 Dec 2021	|
| Raspberry Pi 4 + Accessories	| Ajay 		| 12 Jan 2021 	| 10 Dec 2021 	|
| Raspberry Pi Pico		| Jen 		| 12 Nov 2021 	| 16 Feb 2022 	|
| Track Robot			| Dev 		| 12 Nov 2021 	| 17 Dec 2021 	|
| XT60 Battery			| Ajay 		| 12 Nov 2021 	| 04 Mar 2022	|
| XT60 Battery			| Ajay	 	| 12 Nov 2021 	| 04 Mar 2022	|
| XT60 Battery charger		| Locker 	| 12 Nov 2021 	| 		|
| Tetrix Robot			| Locker 	| 12 Nov 2021 	| 		|
| Raspberry Pi Cam		| Locker 	| 12 Nov 2021 	| 		|
| Logitech Camera		| Ajay	 	| 12 Nov 2021 	| 10 Dec 2022	|
| Tool Bag			| Locker 	| 12 Nov 2021 	| 		|
| Geiger Counter		| Jen 		| 03 Jan 2022 	| 16 Feb 2022	|
| MLX90540 Thermal Camera	| Yaa   	| 12 Jan 2022 	| 14 Jan 2022	|
| Enviro+			| Dev	 	| 12 Jan 2022 	| 		|
| Particulate Matter Sensor	| Locker 	| 04 Mar 2021 	| 		|

</div>

----

## Test Plan

The test plan for the subsystems can be found on their respective repos.

[Dashboard Test Plan](https://github.com/lboroWMEME-TeamProject/Dashboard#Test-Plan)

[Server Test Plan](https://github.com/lboroWMEME-TeamProject/Cloud-Server#Test-Plan)

[Simulated Drone Test Plan](https://github.com/lboroWMEME-TeamProject/Simulated-Drone#Test-Plan)

[Geiger Counter Test Plan](https://github.com/lboroWMEME-TeamProject/Geiger-Counter#Test-Plan)


*The Simulated Drone project was created explicitly to test the server and GUI without the actual drone needing to be present. This way, development for both those parts of the system can commence even before parts for the drone were ordered.*

----


