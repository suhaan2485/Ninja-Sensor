<h1 align="center">
  Ninja Sensor
  <br>
</h1>

A Basic Motion Sensor Interface with buttons and an LCD Screen !

## Key Features:
- Personal Pet !!!!
- **0.96 inch** I2C OLED Display
- **XIAORP2040** Mini Arduino Microcontroller
- **MPU-6050 Board** Motion Tracking Device
- **DHT11 Sensor** For Measuring Humidity and Temparature
- **Cherry MX** Switches
- **2 Layer** PCB
- Cool Ninja Star Shape Design
- Softwares Used - KiCad (10.0.1), Arduino IDE (2.3.10), Google Chrome.

## PCB

Simple 2 Layer PCB Designed in KiCad

### Schematics:

<img width="1737" height="910" alt="image" src="https://github.com/user-attachments/assets/f678b60e-af4c-4ae4-93a9-bc9ecf8d7273" />

### PCB Layout: 

<img width="1977" height="1131" alt="image" src="https://github.com/user-attachments/assets/434c3ecc-7df2-43f8-a9e3-6e2e8f293a65" />

### PCB 3D View:

<img width="1243" height="867" alt="image" src="https://github.com/user-attachments/assets/5b8af084-949d-47b6-a8f2-b86197740288" />


## Bill Of Material (Imported From KiCad)

| Reference | Qty | Value | DNP | Exclude from BOM | Exclude from Board | Footprint | Datasheet | Description | # |
|---|---|---|---|---|---|---|---|---|---|
| J1 | 1 | Conn_01x04_Pin |  |  |  | Imported Parts:Display_128x64_096_I2C |  | Generic connector, single row, 01x04, script generated | 1 |
| J2 | 1 | Conn_01x08_Pin |  |  |  | Connector_PinHeader_2.54mm:PinHeader_1x08_P2.54mm_Vertical |  | Generic connector, single row, 01x08, script generated | 2 |
| R1 | 1 | 10k |  |  |  | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal |  | Resistor | 3 |
| SW1,SW2 | 2 | SW_Push |  |  |  | Button_Switch_Keyboard:SW_Cherry_MX_1.00u_PCB |  | Push button switch, generic, two pins | 4 |
| U1 | 1 | DHT11 |  |  |  | Sensor:Aosong_DHT11_5.5x12.0_P2.54mm | http://akizukidenshi.com/download/ds/aosong/DHT11.pdf | 3.3V to 5.5V, temperature and humidity module, DHT11 | 5 |
| U2 | 1 | XIAO-ESP32-C3-SMD |  |  |  | Imported Parts:XIAO-ESP32-C6-DIP |  |  | 6 |
