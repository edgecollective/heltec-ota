# heltec-ota

Explanation of this is [here](https://lastminuteengineers.com/esp32-ota-web-updater-arduino-ide/)

This is same as ota-web-updater example that comes with Espressif infrastructure for Arduino IDE; only modification is that I've moved the ssid and password into a separate file, 'credentials.h', which needs to be located in same arduino folder and have the following format:

```
const char* host = "esp32";
const char *ssid = "[Your ssid]";
const char *password = "[your password]";
```
