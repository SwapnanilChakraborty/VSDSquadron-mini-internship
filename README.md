# VSDSquadron-mini-internship
![Block diagram](https://github.com/SwapnanilChakraborty/VSDSquadron-mini-internship/assets/167600451/b29bd713-f07e-45f3-8e24-4082b0792b83)
Advanced Weather Station using BME280 Sensor and Live Weather App

Overview
The advanced weather station using the BME280 sensor and a live weather app is a versatile and cost-effective solution for real-time weather monitoring, crucial for sectors like agriculture, aviation, and disaster management. Leveraging the precision of the BME280 sensor, this setup enhances safety, efficiency, and educational opportunities by providing accurate, real-time data on temperature, humidity, and pressure. It serves a broad array of applications from helping farmers in agricultural planning to aiding in STEM education and environmental research. This project is implemented using the BME280 sensor and  VSD Squadron microcontroller board and  functions as the BME280 sensor collects the real time data from the environment and transmits it to the web server through the VSD Squadron board and  I2C communication protocol and the web server is linked with an open weather map through API . 

Components Required

1.	Bread Board
2.	Connecting wires
3.	BME280 sensor
4.	VSD Squadron board

The VSD Squadron development board utilized for the Advanced Weather Station using BME280 sensor project  consists of the CH32V003F4U6 chip with 32-bit RISC-V core based on RV32EC instruction set, optimized for high-performance computing with support for 2-level interrupt nesting and supports 24MHz system main frequency in the product function.
The board operates at a input  voltage between 3.3 volt to 5 volt and is equipped with 15 GPIOS and communication protocols such as I2C,SPI,USART for  versatile connectivity options.
The another core part of the project is the BME280 sensor interfaced with the VSD squadron board operates at a voltage of 3 volt D.C .It  measures relative humidity from 0 to 100% with 3% accuracy along with  barometric pressure from 300 Pa to 1100 hPa with 1% accuracy and 
Temperature from -40 degree Celsius to 85 degree Celsius with an accuracy of 10 degree Celsius .

Circuit Connection for Advanced Weather Station

In the Advanced Weather Station using BME280 senor project ,the Vcc terminal of BME280 sensor is connected to the 3.3V supply of VSD Squadron board and the ground terminal of BME280 is connected with ground terminal of VSD Squadron . In this project we are using I2C communication protocol so the SCL/SCK (Serial Clock)pin of BME280 is connected to PC1 pin in VSD Squadron and SDA/SDI (Serial Data) is connected to the PC2 pin of VSD Squadron board  and the  board is connected to laptop via USB cable .This connection ensures that the VSD Squadron board receives and processes the data from  BME280 sensor and transmits it to the web server via USB cable.

Pin Out Diagram for Advanced Weather Station 

![image](https://github.com/SwapnanilChakraborty/VSDSquadron-mini-internship/assets/167600451/6b7b68c0-cc9d-4ce1-84a9-2425116554e2)

Table for Pin Connection

| BME280 | VSD Squadron |
| --- | --- |
| Vcc | 3.3v |
| Ground | Ground |
| SCL/SCK | PC2 |
| SDA/SDI | PC1 |
