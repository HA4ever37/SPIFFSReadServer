# SPIFFSReadServer
This is an updated version of r-downing/SPIFFSReadServer library to support LittleFS server extension of the ESP8266WebServer library. This is intended to handle 'read-only' static files without the need for a live editor. Of course, files can still be modified programmatically or via other server handlers

Differences between this version and r-downing's version:
* Support LittleFS instead of legacy SPIFFS
* Support ArduinoJson v6
* Fix the library example
