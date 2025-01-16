# AdafruitMetroESP32-DynamixelHat

A HAT designed for the [AdaFruit Metro ESP32-S3](https://learn.adafruit.com/adafruit-metro-esp32-s3) to communicate with Dynamixel servos

![image](https://github.com/user-attachments/assets/1e14d920-3469-4be4-8a81-6ca9415b7f7c)

# Bill of Materails
| Item | Link | Quantity | Unit Cost | Item Cost |
| ---- | ---- | -------- | --------- | --------- |
| TXB0104PWR Level Shifter | [Link](https://www.digikey.com/short/qm0td78w) | 1 | $0.87 | $0.87 | 
| SN74LVC2G241DCTR Tri-state buffer | [Link](https://www.digikey.com/short/1w0w74jb) | 1 | $0.40 | $0.40 | 
| 10k Resistor | [Link](https://www.digikey.com/short/27n7pcz3) | 4 | $0.10 | $0.40 | 
| 0.1 µF Capacitor | [Link](https://www.digikey.com/short/hjtz927q) | 6 | $0.10 | $0.60 | 
| 100 µF Capacitor | [Link](https://www.digikey.com/short/43pqprtd) | 1 | $1.73 | $1.73 | 
| JST Header | [Link](https://www.digikey.com/short/h1hjcqr2) | 3 | $0.46 | $1.38 | 
| 8P Header | [Link](https://www.digikey.com/short/35q99nnb) | 2 | $1.42 | $2.84 | 
| 6P Header | [Link](https://www.digikey.com/short/1hd3z8d7) | 1 | $1.80 | $1.80 | 
| 10P Header | [Link](https://www.digikey.com/short/rm5nhzqt) | 1 | $2.19 | $2.19 | 
| PCB Fab | | 5 | 2 | ~$20 |
| | | | Total Cost | $32.21|

# Assembly
Hand soldering this is not for the faint of heart. If you don't own a hotplate and solder paste I would recommend having your PCB fab doing all the SMD component assembly and then purchasing the 100 µF capacitor and headers to solder yourself. 
Otherwise all components are labeled and assuming your PCB has silk screen printing, it should just be matching footprints. 
A "cheap" hotplate can be found for ~$55 on Amazon and should be sufficient with some cheap solder paste in a syringe to go along.

If the JST connectors don't match the footprint, try inserting them the otherway. Incorrectly soldering them shouldn't cause harm since the 12v line is in the middele regardless but I don't recommend finding out.


