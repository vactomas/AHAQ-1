# AHAQ-1 -> AstroHex Air Quality v1

AHAQ-1 is an air quality station. Currently, it is an on-going project in development.

This device is based on the ESP32-C6 microcontroller. It features SCD4X CO2 sensor, BMP280 for temperature and ambient pressure measurements and SEN55 for PM1-10, NOx and VOCs. Additionaly, there are two I2C expansion ports for additional sensors. There is also a connector for E-Paper display.

ESPhome is the firmware of choice for AHAQ-1. This allows for easy integration with Home Assistant instances.

This repo contains all the necessary files to build and flash this device.
