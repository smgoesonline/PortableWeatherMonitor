# PortableWeatherMonitor
ESP8266WiFi (NodeMCU) based portable weather monitor using a DHT11 sensor, 1.96" I2C OLED, a buzzer and RGB LED.


smgoesonline_pwmon.ino is the C++ code which has to be downloaded and opened in an Arduino IDE environment

Please make sure the end user has installed ESP8266 boards by "ESP8266 community" in the boards manager section of the Arduino.

Then select, NodeMCU 0.9 (ESP-12) module as the upload board on your provided COM port.



Connect OLED to the specified I2C port and provide power and ground.

Connect DHT11 sensor's OUT port to pin D6.

Connect the buzzer's power pin to D7. The other to ground.

Connect the RGB LED's R anode to D4, B anode to D3. Connect the negative pin to ground.



Please make sure the user has installed the libraries needed to work, which are as given:

<Wire.h>
<Adafruit_GFX.h>
<Adafruit_SSD1306.h>
<Adafruit_Sensor.h>
<DHT.h>
