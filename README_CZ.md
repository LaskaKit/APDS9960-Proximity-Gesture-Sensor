# APDS9960 - senzor pro detekci přiblížení, gest, osvětlení i RGB barev

![APDS9960 modul](https://github.com/LaskaKit/APDS9960-Proximity-Gesture-Sensor/blob/main/img/LaskaKit-APDS9960-Proximity-Gesture-Sensor-1.jpg)

Jeden senzor a kolik toho umí! Detekuje přiblížení, rozpoznává gesta, měří osvětlení i rozpoznává barvy - APDS9960. Teď i na našem modulu s uŠup konektory pro jednoduché připojení k dalším modulům a deskám s [ESP32](https://www.laskakit.cz/vyhledavani/?string=esp32) nebo [ESP8266](https://www.laskakit.cz/vyhledavani/?string=esp8266).</br>
Díky [redukci](https://www.laskakit.cz/--sup--stemma-qt--qwiic-jst-sh-4-pin-kabel-dupont-samice/) lze samozřejmě modul připojit i k dalším deskám jako je populární [Arduino Uno, Nano, Micro](https://www.laskakit.cz/vyhledavani/?string=arduino%20uno) nebo RaspberryPi či [RockPi](https://www.laskakit.cz/vyhledavani/?string=rockpi).</br>

Náš modul APDS9960-Proximity-Gesture-Sensor má I2C adresu 0x39. Na desce dále najdeš naše [dva uŠup konektory](https://blog.laskakit.cz/predstavujeme-univerzalni-konektor-pro-propojeni-modulu-a-cidel-%ce%bcsup/). Díky nim můžeš připojit další a další moduly. Které? 
Třeba [BME688 - Senzor tlaku, teploty, vlhkosti a kvalitu vzduchu](https://www.laskakit.cz/laskakit-bme688-senzor-tlaku--teploty--vlhkosti-a-kvalitu-vzduchu/), [SGP41 - VOC a Nox senzor kvality ovzduší](https://www.laskakit.cz/laskakit-sgp41-voc-a-nox-senzor-kvality-ovzdusi/) a všechna ta data můžeš zobrazit na [OLED displeji 1.3"](https://www.laskakit.cz/laskakit-oled-displej-128x64-1-3--i2c/?variantId=11903).

Modul s APDS9960 má zadní straně propojku pro připojení pull-up rezistorů na I2C sběrnici. Ta je ve z výroby propojená. Pokud pull-up rezistory použít nechceš, stačí proškrábnout cestu mezi pájecími ploškami mostu.

Mezi podporované knihovny v Arduino IDE patří</br>
https://github.com/arduino-libraries/Arduino_APDS9960</br>
https://github.com/sparkfun/SparkFun_APDS-9960_Sensor_Arduino_Library</br>
https://github.com/adafruit/Adafruit_APDS9960</br>

![Bottom strana modulu](https://github.com/LaskaKit/APDS9960-Proximity-Gesture-Sensor/blob/main/img/LaskaKit-APDS9960-Proximity-Gesture-Sensor-3.jpg)
