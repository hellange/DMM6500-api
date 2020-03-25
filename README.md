This sketch connects to a DMM6500
using an a W5500 based ethernet board connnected to a Teensy 3.2.
This test sketch is based on POSTING to /ajax_proc (undocumented?) API.

Just a first test to see if it`s possible to read data from DMM6500 though its ethernet port.
 
Tested with Teensy 3.2.
Connected a W5500 based board to standard SPI port. CS=10. 3.3V power.
Compiled with Arduino IDE 1.8.5 with Teensyduino 1.5.1 (has latest Ethernet library)

Replace IPAddress server(192,168,1,106) with the IP address of your DMM6500.

Also replace client.println("Host: 192.168.1.106");


W5500 based board bought at https://www.aliexpress.com/item/32950316631.html?spm=a2g0s.9042311.0.0.37054c4dicCi6O
From description: "USR-ES1 is the Ethernet module of a SPI interface, interface is TTL level of 3.3V, power supply voltage of +3.3V, please ensure that the current is not less than 200mA, voltage is continuous and stable +3.3V"

