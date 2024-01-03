# ESP8266_Beginner
***
#### 1. Initial Setup steps:
* In "Arduino IDE": 
  - File -> Preferences -> Add link "http://arduino.esp8266.com/stable/package_esp8266com_index.json"
  - Board -> select -> NodeMCU 1.0 (ESP12E...)
* In "VSCode IDE": 
  - Install extension PlatformIO IDE
  - Note:
  - 
#### 2. Start Code:
- Declare pins and initial states.
- Basic commands:
  - pinMode(2, OUPUT);
  - digitalWrite(2, HIGH);
  - delay(1000); //delay 1s