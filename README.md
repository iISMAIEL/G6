# Group 6 (Blistered Basilisk)

~~~~~~~~~~~~
Monitor temperature with ease using TempTrack.
~~~~~~~~~~~~

Group members:  
1- ISMAIEL HAITHAM EISSA - A19EE4055  
2- NORDURRATUL HIKMAH BINTI MUSTAFFA -A19EE0382  
3- SAYYID JA'FAR SADIQ - A19EE0435


## Problem Statement

The project aims to develop a system for monitoring temperature in two different environments using sensors 
and transmitting the data to a cloud-based system. The collected data will be displayed in real-time 
using Pythonanywhere, Django, and Grafana. The main challenge is to ensure accurate and reliable data collection 
and transmission while providing an intuitive and user-friendly interface for data visualization and analysis.

## System Architecture

Since the objective of this IoT project is to measure and monitor the temperature in both indoor and outdoor environments. 
Two temperature sensors were utilized. The collected temperature data from the sensors will be transmitted to two Arduino 
boards, which will use the MQTT protocol to upload the data to the cloud-based InfluxDB system. 
The project also aims to display the collected temperature data in a user-friendly manner using 
the Pythonanywhere, Django, and Grafana frameworks. 
![WhatsApp Image 2023-05-02 at 2 47 04 PM](https://user-images.githubusercontent.com/129519813/236999098-e8237402-c819-43cf-87aa-c90b150b33f8.jpeg)

## Sensor

The Sensors used in this project will be either the temperature/humidity sensors DHT11/22 or the TMP36 sensor. They're connected
to two Arduino Uno boards and each board will be placed on indoors and outdoors of an area, respectively. the sensors will be 
operating for 2 weeks for temperature sensing and collecting for the upcoming Grafana dashboard for analysis.

![Project1Sensor drawio](https://github.com/iISMAIEL/G6/assets/89000456/87024943-247e-4851-b20a-05a15faa6283)

## Cloud Platform

Link: http://ismaiel.pythonanywhere.com/playground/hello/

Video: https://youtu.be/Op_G1_dshXM

## Dashboard  
### InfluxDB + GRAFANA DASHBOARD 
https://datalogd.readthedocs.io/en/latest/recipes/win_serial_influxdb_grafana.html
![Figma basics (1)](https://user-images.githubusercontent.com/124263652/236373656-b9343815-68ac-4caf-86bc-162a757ad881.png)
