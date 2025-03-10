# Temp-Sensor

COMANY:CODTECH IT SOLUTIONS

NAME:ASHWINI NAIK

INTERN ID:CT12009

DOMAIN: EMBEDDED SYSTEM

DURATION:4 WEEKS

MENTOR:NEELA SANTHOSH KUMAR

**Temperature Monitoring System: 

Instructions Required Components:
*DHT11 or DHT22 Sensor:
A basic temperature and humidity sensor.

*Arduino (e.g., Uno, Nano): 
The microcontroller to read data from the sensor and display the output.
16x2 LCD with I2C module: To display temperature data.

*Wires and Breadboard: 
For connecting the components.
(Optional) Arduino IDE: For programming the Arduino.

**Wiring the Components:
DHT11 (or DHT22) Sensor:
VCC pin to 5V on Arduino.
GND pin to GND on Arduino.
DATA pin to Digital Pin 2 on Arduino (or any other digital pin you choose).
16x2 LCD with I2C:
GND to GND on Arduino.
VCC to 5V on Arduino.
SDA to A4 on Arduino (for Arduino Uno).
SCL to A5 on Arduino (for Arduino Uno).

**Step-by-Step Instructions to Set Up the Temperature Monitoring System:
1. Install Libraries:
You need to install two libraries for the system:

DHT sensor library to read data from the DHT11 sensor.
LiquidCrystal_I2C library to control the LCD via I2C.
To install them:

Go to Sketch > Include Library > Manage Libraries.
Search for DHT sensor library and LiquidCrystal_I2C and install both.

2. Arduino Code for LCD Display:
This example will read the temperature from the DHT11 sensor and display it on the LCD screen. You can also modify the code to display it on the Serial Monitor instead of the LCD, depending on your choice.

3. Upload the Code:
After writing the code, click the Upload button in the Arduino IDE.
Once the code is uploaded successfully, the LCD should display the temperature in Celsius.

**OUTPUT:
