# esp_mqtt_doppler

I use this project to create a motion sensor that communicates over WiFi with an MQTT broker.
My Home Assistant server subscribes to messages from the WeMOS and can react when the doppler sensor detects motion.

## Hardware, currently

* WeMOS D1 R1 Arduino (based on the ESP8266)
* Doppler motion sensor ($1.95 from MPJA)

## TODO

* Document how to configure in Home Assistant
* Remove unused MQTT PUB messages
* Do an ESP32 version
* Document the hookup. It's so simple almost not worth it. Almost. :-)
* Test on 24 VDC so it can be deployed on a led strip power supply
