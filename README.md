BMP085
======

It is surprisingly difficult to find an actually working BMP085 code for the Raspberry Pi on the net. Here is my working version. It uses the <a href="https://projects.drogon.net/raspberry-pi/wiringpi/i2c-library/">wiringPi I2C library</a>, you'll have to have that installed for this to work. The code is based on the datasheet of BMP085.

There are two versions the MV_bmp085.c is generic one, which displays the local pressure and the WS_bmp085.c is one I wrote for my windowsill weather station, that requires an altitude in meters as a parameter to give the atmospheric pressure at sea level.
