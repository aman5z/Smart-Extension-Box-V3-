Smart Extension Box V3 

https://aman5z.blogspot.com/2024/09/projects.html


 Smart Extension Box V3 For this project, I used a GoldMedal brand extension box with 6 x 3-pin sockets. Originally, it had a single switch to control all the sockets at once. I upgraded it using a 4-channel + 2-channel=6 channel relay, an ESP32 dev board, and an AC to DC 5V 2A adapter. I added a reset switch, a USB-A port for reprogramming the device via Arduino IDE, and an external port to avoid opening the box each time.

The extension box now has individual control switches thanks to an IR receiver module (TSOP) and a small generic IR remote. I extracted the IR values and assigned them to each of the six sockets, using the '0' button to turn off all sockets at once. The box can also be controlled via the ESP RainMaker app, Alexa, or Google Assistant, allowing for timers and automation.
