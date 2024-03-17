# Pepper
New Docker Image to connect and control pepper robot with pepper python SDK included.

## Summary
This document is about the project using Pepper Robot ( a semi-humanoid robot), to connect and control using IoT services.

The Pepper Robot woks on python 2.7 and it can be programmed using pynaoqi-python SDK and SSH commands.  The Choregraphe Software can also be used to program it

Choregraphe Software and Python -SDK :  [Downloads Softwares | Aldebaran](https://www.aldebaran.com/en/support/nao-6/downloads-softwares)

Python SDK Installation Guide ; [Python SDK - Installation Guide — Aldebaran 2.5.11.14a documentation](http://doc.aldebaran.com/2-5/dev/python/install_guide.html)

    

## Features
- Connect to Pepper Robot
- Connect to WiFi network
- Connect to MQTT Service (Homie Conventions)
- Connect to OpenHAB
- Using Python SDK with python scripts


## Software
Refer Github : https://github.com/care-group/Pepper-Docker.git


## How to Use
1. Open the Docker web interface from https://localhost:5000/

![image](https://github.com/carolsanthosh/Pepper-Robot/assets/42265511/d32a9de5-0237-41da-943e-8670003d5680)

2. **Connect Robot** section is for connecting to the robot with basic essential controls
   ![image](https://github.com/carolsanthosh/Pepper-Robot/assets/42265511/8182ee55-0115-4855-a422-37b3cae23d26)

3. **Connect MQTT** section is to conenct the robot to MQTT server for openhab (Create a openHAB thing)
   ![image](https://github.com/carolsanthosh/Pepper-Robot/assets/42265511/8e693dc4-1c1b-4eff-82ac-af33caea1c80)

4. **Uploaded Files** section is for uploading the python scripts and running it throgh docker


![image](https://github.com/carolsanthosh/Pepper-Robot/assets/42265511/f2dbb78e-3be8-4c8c-b178-5192d5dba7b8)

   **Upload a File** - To upload pyhton files, which will be displayed in the **Uploaded Files** section below and can be controlled wuing button at the bottom **(Run, Stop, Delete)**
  
   
   ![image](https://github.com/carolsanthosh/Pepper-Robot/assets/42265511/5a3a896c-4c16-43dd-82cc-44ebc796d931)


7. **Behaviors Files** section to run applications created using Choregraphe software


    ![image](https://github.com/carolsanthosh/Pepper-Robot/assets/42265511/a8c4558e-3419-41bd-be1e-fb47e1898415)

    The drop down list provides the list of applicatons saved in the robot with controls to **run or stop**

    ![image](https://github.com/carolsanthosh/Pepper-Robot/assets/42265511/7637b6ad-4128-4f89-b7f2-bc50fc172156)

 
