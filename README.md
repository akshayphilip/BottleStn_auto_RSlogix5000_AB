# BottleStn_auto_RSLogix5000_Allen_bradley

In this project i have fully automated a bottle filling station , using allen bradley plc , and for programming the ladder logic i have use the RSLogix5000, for the visual experience i have used factory talk view from the allen bradley

## **Table of contents**
1. [Demonstration link](#demonstration-video)
1. [About the Project](#about-the-project)
1. [walking Beam (Station 1)](#walking-beamstation-1)
1. [Filling station](#filling-station-station-2)



### **Demonstration video**

[![demo_youtube](https://github.com/akshayphilip/BottleStn_auto_RSlogix5000_AB/blob/main/images/bottle_station1.PNG)](https://www.youtube.com/watch?v=x3s2e_BYs_U&ab_channel=AkshayPhilip)

---
### **About the Project**

This project i have designed when i was doing Robotics and Industrial Automation(Co-op) at Conestoga college, the project task was to design a fully automated system, using allen bradley PLC , for create programme i have used RSlogix5000 and for the visal interface i have used factory talk view.

For this project i have divided the programming part into four stations, the first station refers to the walking beam, the 2nd part , it is the bottle filling station, the 3rd station is cap insert station and finally station is cap tighting station, for more details on station will provided below 

---

### **Walking Beam(Station 1)**

In this station , used to move the beam horizontally according to the ladder logic, there is a clamp which helps to hold the bottle tight so that i make sure that bottle are holded at correct position and moved from one station to other properly, snap of the walking beam logic is provided below

![walking_beam](https://github.com/akshayphilip/BottleStn_auto_RSlogix5000_AB/blob/main/images/Walking_beam.PNG)

---

### **Filling station (station 2)**

In this station, after the walking picks the empty bottle and put the bottle station for theh filling , the sensor will detect the presence of the bottle and starts to the fill the bottle , when it reaches certian position it plc will tell the filling device to stop and retracting the water filling tube, some snaps of the ladder logic and filling station is given below

#### water is filling the station
![water_filling_station](https://github.com/akshayphilip/BottleStn_auto_RSlogix5000_AB/blob/main/images/water_filling.PNG)

#### filling station ladder logic

![water_filling_station_ladder_logic](https://github.com/akshayphilip/BottleStn_auto_RSlogix5000_AB/blob/main/images/Fill_Station.PNG)

---

