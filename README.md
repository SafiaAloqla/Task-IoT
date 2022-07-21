# Task-IoT
Task speech to text and Algorithm
# Install Arduino IDE
# Installing ESP32 Add-on in Arduino IDE
In your Arduino IDE, go to File> Preferences
Enter the following into the  “Additional Board Manager URLs” field:  (https://dl.espressif.com/dl/package_esp32_index.json )
click the “OK” button
Open the Boards Manager. Go to Tools > Board > Boards Manager
Search for ESP32 and press install button for the “ESP32 by Espressif Systems"
It should be installed after a few seconds.
# Testing the Installation
Select your Board in Tools > Board menu ( Arduino Uno > ESP 32 Arduino)
Connect the piece with the wire
Select the Port 
 IF you don’t see the COM Port in your Arduino IDE
 THEN you need to install the CP210x USB to UART Bridge VCP Drivers
 Open the following example under File > Examples > WiFi (ESP32) > WiFiScan
A new sketch opens in your Arduino IDE
 Press the Upload button in the Arduino IDE, Wait a few seconds while the code compiles and uploads to your board.
IF everything expected, 
THEN you should see a “Done uploading.” message.
Open the Arduino IDE Serial Monitor at a baud rate of 115200
Press the ESP32 on-board Enable button and you should see the networks available near your ESP32
# ESP32 is working
