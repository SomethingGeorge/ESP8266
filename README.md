# ESP8266
Configuring Wifi IOT Device
Purchase a ESP8266 Board (my board came from Amazon and is by Hiletgo)
Initialize the board and flash using these instructions (http://hiletgo.com/ProductDetail/1906570.html)
Note: Flash utility for 64 bit Windows has been uploaded

***********INSTRUCTIONS HERE ALSO**************
Brand Name:  HiLetgo 

UPC :703681358704

Module: 3-01-0268



Instruction & Steps of How to use:

1. Download the Arduino IDE, the latest version. 

2. Install the IDE

3. Set up your Arduino IDE as: Go to File->Preferences and copy the URL below to get the ESP board manager extensions: http://arduino.esp8266.com/stable/package_esp8266com_index.json Placing the http:// before the URL lets the Arduino IDE use it...otherwise it gives you a protocol error.

4. Go to Tools > Board > Board Manager> Type "esp8266" and download the Community esp8266 and install. 

5. Set up your chip as:

Tools -> Board -> NodeMCU 1.0 (ESP-12E Module)

Tools -> Flash Size -> 4M (3M SPIFFS)

Tools -> CPU Frequency -> 80 Mhz

Tools -> Upload Speed -> 921600

Tools-->Port--> (whatever it is)

6. Download and run the 32 bit flasher exe at Github(Search for nodemcu/nodemcu-flasher/tree/master/ at Github)

github.com/nodemcu/nodemcu-flasher/tree/master/Win32/Release 

Or download and run the 64 bit flasher exe at: 

github.com/nodemcu/nodemcu-flasher/tree/master/Win64/Release

7. In Arduino IDE, look for the old fashioned Blink program. Load, compile and upload. 

8. Go to FILE> EXAMPLES> ESP8266> BLINK, it will start blinking. 
