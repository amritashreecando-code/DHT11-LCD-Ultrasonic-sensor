# DHT11-LCD-Ultrasonic-sensor
# DHT11 + LCD + Ultrasonic Sensor using ESP8266 NodeMCU

## 📌 Project Description
This project reads temperature and humidity using the DHT11 sensor 
and measures distance using the HC-SR04 ultrasonic sensor. 
The values are displayed on a 16x2 LCD display using ESP8266 NodeMCU.

## 🛠️ Components Used
- ESP8266 NodeMCU
- DHT11 Temperature & Humidity Sensor
- HC-SR04 Ultrasonic Sensor
- 16x2 LCD Display with I2C module
- Jumper Wires
- Breadboard

## 📌 Pin Connections

### DHT11
| DHT11 Pin | NodeMCU Pin |
|-----------|-------------|
| VCC       | 3.3V        |
| GND       | GND         |
| DATA      | D4          |

### HC-SR04
| HC-SR04 Pin | NodeMCU Pin |
|-------------|-------------|
| VCC         | VIN (5V)    |
| GND         | GND         |
| TRIG        | D6          |
| ECHO        | D7          |

### LCD (I2C)
| LCD Pin | NodeMCU Pin |
|---------|-------------|
| VCC     | VIN (5V)    |
| GND     | GND         |
| SDA     | D2          |
| SCL     | D1          |

## 💻 Libraries Used
- DHT sensor library by Adafruit
- LiquidCrystal_I2C
- Wire.h

## 🚀 How to Run
1. Install the above libraries in Arduino IDE
2. Connect components as per pin connections above
3. Upload the .ino file to NodeMCU
4. Open Serial Monitor at 115200 baud rate
