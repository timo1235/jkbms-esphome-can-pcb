# JK-BMS ESP32 CAN project

<img src="images/ESP32%20JK-BMS-7-500px.jpg" width="300" />
<img src="images/ESP32%20JK-BMS-6-500px.jpg" width="300" />
<img src="images/ESP32%20JK-BMS-5-500px.jpg" width="300" />
<img src="images/ESP32%20JK-BMS-2-500px.jpg" width="300" />
<img src="images/ESP32%20JK-BMS-3-500px.jpg" width="300" />
<img src="images/ESP32%20JK-BMS-4-500px.jpg" width="300" />
<img src="images/ESP32%20JK-BMS-500px.jpg" width="300" />

This repository contains all the files I used to create a pcb and a housing for the [esphome jk bms project](https://github.com/Uksa007/esphome-jk-bms-can).

## pcb features

- RJ45 connector for CAN bus
- Screw terminal for CAN bus
- Screw terminal for JK-BMS RS485 Signal(also used for power, since the JK-BMS has the battery voltage on the RS485 port socket)
- Integrated dc dc converter for 5V
- Integrated CAN chip

## electrical characteristics

- The ESP32 can be powered by the JK-BMS RS485 signal, since the JK-BMS has the battery voltage on the RS485 port socket
  - max voltage is 60V. If the battery has higher voltage, do not connect the VIN terminal with the JK-BMS
- The ESP32 can be powered via USB
