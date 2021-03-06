# AMAleg
DIY Macchina A0 Clone built from parts attainable from amazon. <br><br>

<p align="center">
  <img src="https://github.com/Switchleg1/AMAleg/blob/main/screenshot1.jpg?raw=true" width="200" title="hover text">
  <img src="https://github.com/Switchleg1/AMAleg/blob/main/screenshot2.jpg?raw=true" width="200" title="hover text">
  <img src="https://github.com/Switchleg1/AMAleg/blob/main/screenshot3.jpg?raw=true" width="200" title="hover text">
  <img src="https://github.com/Switchleg1/AMAleg/blob/main/screenshot4.jpg?raw=true" width="200" title="hover text">
</p><br>

Case Models: <br>
For OBD connectors with 1.5mm flanges and the smaller KeeYee esp32 boards<br>
Top (you may need to oversize 1% depending on material and printer calibration) <br>
https://github.com/Switchleg1/AMAleg/blob/main/SL1.3.5-top.STL<br>
Bottom (x2) <br>
https://github.com/Switchleg1/AMAleg/blob/main/SL1.3.5-bottom_half.STL<br><br>

For OBD connectors with 1.5mm flanges and the larger esp32 boards with mounting holes<br>
Top (you may need to oversize 1% depending on material and printer calibration) <br>
https://github.com/Switchleg1/AMAleg/blob/main/SL1.5-top.STL<br>
Bottom (x2) <br>
https://github.com/Switchleg1/AMAleg/blob/main/SL1.5-bottom_half.STL<br><br>

For OBD connectors with 2mm flanges (not common)<br>
Top <br>
https://github.com/Switchleg1/AMAleg/blob/main/top.STL<br>
Bottom (x2) <br>
https://github.com/Switchleg1/AMAleg/blob/main/bottom_half.STL<br><br>

Parts list (quantity 1 of each): <br>
Any ESP32 dev board <br>
https://www.amazon.ca/KeeYees-Development-Bluetooth-Microcontroller-ESP-WROOM-32/dp/B07PP1R8YK/ref=sr_1_20?crid=22P4LA1F8VBNC&keywords=esp32&qid=1643595911&sprefix=esp32%2Caps%2C105&sr=8-20 <br><br>
SN65HVD230 breakout board - **Watch out for fakes, take note of how long they have been selling for and if they are less than $3usd each it is probably fake, if the last line of the chip reads 'ctcv04' it is a fake (though there are more fakes these have been tested).<br>
It appears all of the square boards are probably fakes at the moment and the only luck we have seen are with the rectangle board. ** 
<img src="https://github.com/Switchleg1/AMAleg/blob/main/canboard.jpg?raw=true" width="100" title="hover text"><br>
https://www.amazon.ca/SN65HVD230-CAN-Board-Communication-Development/dp/B00KM6XMXO/ref=sr_1_5?keywords=waveshare+sn65hvd230&qid=1651667489&sprefix=sn65%2Caps%2C108&sr=8-5 <br><br>
Any MP1584 based buck converter <br>
https://www.amazon.ca/eBoot-MP1584EN-Converter-Adjustable-Module/dp/B01MQGMOKI/ref=sr_1_9?crid=192T7TLTFMKHE&keywords=buck+converter&qid=1643596906&sprefix=buck+converter%2Caps%2C105&sr=8-9 <br><br>
OBD2 connector (can also be taken from an elm adapter) <br>
https://www.sparkfun.com/products/9911 <br><br>
Schottky or fast recovery diode (1Amp 20v) 1N5819, SR100, UF4004, etc <br>
https://www.amazon.ca/1N5819-Schottky-Barrier-Rectifier-DO-204AL/dp/B07RL3SCL4/ref=mp_s_a_1_5?crid=AX2MPSXQXPUM&keywords=1+amp+schottky+diode&qid=1643646733&sprefix=1amp+schottky+diode%2Caps%2C267&sr=8-5<br><br>

Wire diagram:<br>
<p align="center">
  <img src="https://github.com/Switchleg1/AMAleg/blob/main/diagram.jpg?raw=true" width="2000" title="hover text">
</p><br>

After assembling remember to set the voltage regulator anywhere from 5-5.5v (turn knob clockwise by 1/10th of a turn) and flash the latest firmware https://github.com/Switchleg1/esp32-isotp-ble-bridge


Print layout:<br>
Always print with logo facing up with support material.  If printing with ABS i recommend a peelable raft.
<p align="center">
  <img src="https://github.com/Switchleg1/AMAleg/blob/main/print.jpg?raw=true" width="2000" title="hover text">
</p><br>
