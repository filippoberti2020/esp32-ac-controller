# Esp32 Air Conditioner controller
Project to control an air conditioner locally and remotely.
If you don't have Home Assistant this project is perfect for you because it offers a well-done, minimalist interface that allows you to control and manage your air conditioner

## Parts:
- Esp32
- IR Reciver (to read and store the AC command)
- IR Transmitter (to send command to the AC)
- BME280

## Project Goal:
- Monitor room temperature
- Schedule power on and off
- Possibility to turn it on from remote


## Implementation:
The esp32 will be use as a web server to host the web interface and to control the air conditioner and temperature sensor.
 

## Interface preview:
![Desktop layout](/AC-RemoteControlUx.png?raw=true "Title")
  ```
  Desktop Web Interface
  ```
![Mobile layout](/AC-RemoteControlUxMobile.png?raw=true "Title")
 ```
  Mobile Web Interface
  ```
  
### Consulted Digital Resources :
[Temperature Graph](https://randomnerdtutorials.com/esp32-esp8266-plot-chart-web-server/)
[Cloning AC command](https://community.dfrobot.com/makelog-308344.html)
