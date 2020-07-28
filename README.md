# ESP8266 ESP-01 - Flashing method by FRUD

![preview 1](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/01.jpg)

# You will need

1 - USB-UART PL2303 3.3V or another USB to TTL converter

![preview 2](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/02.jpg)

2 - ESP8266 ESP-01

![preview 3](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/03.jpg)

3 - Wires

![preview 4](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/04.jpg)

4 - Package content

https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/ESP-01_wifi-serial_bridge.zip

# Drivers setup

1 - Most likely, after connecting TTL converter to USB, you will see the following picture

![preview 5](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/05.jpg)

2 - This means you need to install the correct driver...

![preview 6](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/06.jpg)

![preview 7](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/07.jpg)

![preview 8](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/08.jpg)

Sorry, I don't know much about windows, so no comments. ))

# Flashing ESP-01 module

1 - Connect ESP-01 to PL2303 according to the following scheme

![preview 9](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/09.jpg)

2- Connect PL2303 to USB. And Run TCP2UARTFlasher.exe

![preview 10](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/10.jpg)


3 - Go to the Config tab and select the firmware binaries from downloaded package. Do not forget to check the boxes on the left and register the correct addresses on the right (indicated in the names of the binary files)

![preview 11](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/11.jpg)


4 - Go back to the Operation tab and press Flash (F)

![preview 12](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/12.jpg)


5 - We are waiting for the completion of the process

![preview 14](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/14.jpg)

6 - Remove the PL2303 from the USB port. Disconnect the GND wire from GPIO0 of ESP-01

![preview 16](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/16.jpg)

# WEB Server content flashing

1 - Connect TTL converter (with wired ESP-01) to USB.

2 - Ower WiFi connect to the ESP8266.

3 - Open your browser and enter the address 192.168.4.1/fsupload. Enter Login <b>ESP8266</b> and Password <b>0123456789</b> and we see the following picture.

![preview 17](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/17.jpg)

4 - Select the WEBFiles.bin file from downloaded package and click Upload

![preview 18](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/18.jpg)

5 - After flashing, ESP-01 now automaticaly reboot.

![preview 19](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/19.jpg)

6 - Cross your fingers and enter the address 192.168.4.1 in the browser...

![preview 20](https://github.com/helimania/ESP8266-ESP-01-Flash/blob/master/images/20.jpg)


Do not forget! Default name - ESP8266 and password - 0123456789, which can be set on the WIFI Settings tab

I was glad to help you! Enjoy)))

Source by ALex FRUD:
- part 1 https://www.drive2.ru/b/541373138311578820/
- part 2 https://www.drive2.ru/b/541376986602274976/
- part 3 https://www.drive2.ru/b/541378635869717687/
