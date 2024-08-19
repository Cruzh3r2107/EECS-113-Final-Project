# EECS-113-Final-Project
Fianl video link was removed.

The project is a Building Management System implementation using a Raspberry Pi 3B+ and sensors  like PIR Infrared Motion Detector with LED Indicator, the Infrared Motion Sensor can detect the heat  signatures emitted by living humans within the infrared spectrum, the DHT -11, to read Temperature  and Humidity data.
 It also utilizes the CIMIS API to retrieve weather data, specifically humidity, for 
more accurate monitoring. The goal of the project is to monitor and control the environment within a 
building to optimize energy efficiency, comfort, and safety.

Control of the HVAC (Heating, Ventilation, and Air Conditioning) system is the focus of the BMS. 
Based on the target temperature and the current weather, it modifies the HVAC system's functioning. 
The CIMIS API offers extra meteorological data for enhanced climate control, and the system uses 
temperature and humidity sensors to monitor the indoor environment. By calculating the energy 
consumption and related costs of the HVAC system, the BMS combines energy consumption 
monitoring. Users can use buttons to change the desired temperature, and an LCD screen shows real-time feedback.

Additionally, the system manages door/window sensor events. It recognizes changes in the open or 
closed condition of doors and windows, which may have an impact on how well the HVAC system 
functions. To reduce energy waste, the BMS cuts off the HVAC system whenever the sensors detect an 
open door or window. A fire alarm feature is also included in the BMS. The BMS activates a fire alarm 
if the weather indicates a potential fire threat (for example, a high weather index). It activates the 
door/window status to "OPEN" and issues warnings visually and audibly via the LCD screen and LEDs.

The project prioritizes user comfort and safety while also maximizing energy economy by modifying 
the HVAC system in response to current conditions. The BMS contributes to the maintenance of a 
comfortable and secure indoor environment while minimizing energy loss by integrating a variety of 
sensors and clever control algorithms.
