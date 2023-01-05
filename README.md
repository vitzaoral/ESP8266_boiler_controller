# Solar powered meteo station with ESP8266 Wemos D1 Mini Pro

TODO

## 🚀 12.2022 - UPDATE TO BLYNK 2.0 🚀
Project was updated to the new version of [Blynk 2.0](https://docs.blynk.io/en/)

IoT meteo station system based on ESP8266 Wemos D1 Mini Pro. Checks temperature, humidity and pressure. Data are sent to Blynk and ThingSpeak channel (via [Webhook widget](http://docs.blynk.cc/#widgets-other-webhook)) every minute, then is used deep sleep. Project is free to use, coded in C++, created in Visual Code with [PlatfomIO IDE](http://docs.platformio.org/en/latest/ide/vscode.html).

> To build a project, you need to download all the necessary libraries and create the _settings.cpp_ file in the _src_ folder:

```c++
// Meteo station project settings
struct Settings
{
    const char *ssid = "WIFI ssid";
    const char *password = "WIFI password";
    const char *blynkAuth = "You Blynk Auth";
    const char *version = "2.0.1";
};
```

### Currents list:

- [Wemos D1 Mini Pro with antenna](https://www.aliexpress.com/item/WEMOS-D1-Mini-Pro-16M-Bytes-External-Antenna-Connector-ESP8266-WIFI-IoT-Board/32747247131.html)

### Schema:

![Schema](https://github.com/vitzaoral/metheo-station/blob/master/schema/meteo_schema.jpg)

### PCB circuit:

![PCB 1](https://github.com/vitzaoral/metheo-station/blob/master/schema/pcb_1.jpg)

### Blynk:

![Blynk project](https://github.com/vitzaoral/metheo-station/blob/master/schema/blynk.jpg)
