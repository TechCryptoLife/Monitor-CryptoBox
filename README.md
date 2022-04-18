# Monitor-CryptoBox
![Image of setup](https://github.com/TechCryptoLife/Monitor-CryptoBox/blob/main/pictures/IMG_1029.jpg)
![Image of monitoring page](https://github.com/TechCryptoLife/Monitor-CryptoBox/blob/main/pictures/cryptobox.PNG)
Monitoring temperature, barometric pressure and altitude using BMP280 and ESP8266

## Why did I make this?
I wanted to monitor my self created CryptoBox that lives outside on the balcony. Inside the CrytoBox are some of my crypto miners that mostly use radio frequencies to earn different cryptocurrencies.

I would like to better understanding what the conditions inside my CryptoBox are and know if it is safe to use without damaging the crypto miners hardware.

As I said, I already had the self made CryptoBox created in an earlier stage, but I would really like to keep an eye on it using different sensors and data which is why this is an awesome and really usefull Data Science for Internet of Things project.


## Hardware

* ESP8266 nodemcu v3 1.0

![Image of ESP8266](https://github.com/TechCryptoLife/Monitor-CryptoBox/blob/main/pictures/7b74ebed6e86a9d72e1c1ee2b67b9f10d552dab5.jpg)

The ESP8266 is a microcontroller that can connect to WiFi using the integrated WLAN adapter which makes it easy to send and retrieve data from.


* BMP280

![Image of BMP280](https://github.com/TechCryptoLife/Monitor-CryptoBox/blob/main/pictures/DEBO_BMP280_01.png)

BPM280 is a sensor which measures: temperature, barometric pressure and altitude

## Software
* [Platform io](https://platformio.org/install/ide?install=vscode)
* [Visual Studio Code](https://code.visualstudio.com/)
I used Visual Studio Code together with the extension Platform io because I really like working with those 2 tools, they have so much ease of use built into it and I have used them in the past.
* [Thingspeak](https://thingspeak.com/)
Thingspeak is an easy and free to use platform to make something visual from raw data which is why I used it.

## Web monitoring / charting:
[ThingSpeak Monitoring page](https://thingspeak.com/channels/1705241).


## Sources:
https://pypi.org/project/RPi.bme280/
https://github.com/rm-hull/weatherstation
https://www.raspberrypi-spy.co.uk/2016/07/using-bme280-i2c-temperature-pressure-sensor-in-python/#:~:text=The%20BME280%20device%20is%20a,read%20the%20data%20using%20Python.
http://domoticx.com/raspberry-pi-temperatuur-sensor-ds18b20-uitlezen/
https://www.circuitbasics.com/raspberry-pi-ds18b20-temperature-sensor-tutorial/
https://platformio.org
https://code.visualstudio.com/
https://thingspeak.com/
