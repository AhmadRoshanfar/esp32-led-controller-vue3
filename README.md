# LED Controller with ESP32 HTTP Webserver

## Website Compilation
```
$ cd front/led 
$ npm run build 
```

## Wifi Configuration
```
$ idf.py menuconfig 
Exmaple Connection -> Enter SSID and Password of your wifi 
```
## Build and Flash
```
$ idf.py build flash monitor
```
![LED Webserver Image](led.png "LED Webserver Image")
