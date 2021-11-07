# LED Controller with ESP32 HTTP Webserver

## Website Compilation
```
$ cd front/led <br/>
$ npm run build <br/>
```

## Wifi Configuration
```
$ idf.py menuconfig <br/>
Exmaple Connection -> Enter SSID and Password of your wifi <br/>
```
## Build and Flash
```
$ idf.py build flash monitor <br/>
```
![LED Webserver Image](led.png "LED Webserver Image")
